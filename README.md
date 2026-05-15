# Hi, I'm Mitul Sendilkumar.

> *Robotics researcher. Embedded systems engineer. Gap year.*  
> San Antonio, TX · [mitulisavailable@gmail.com](mailto:mitulisavailable@gmail.com) · [LinkedIn](https://www.linkedin.com/in/mitul-sendilkumar) · [GitHub](https://github.com/MiddleSender45)

---

I build autonomous robotic systems and embedded computer vision stacks — the kind that have to work in the real world, not just in simulation.

Right now I'm using my gap year to do the research I actually care about: maritime rescue ASVs, planetary rover autonomy, and vision-language-action models on prosthetics. No coursework deadlines, no fluff — just deep, focused engineering work.

---

## What I'm Working On

### 🚤 MARLIN — Autonomous Surface Vehicle for Drowning Detection
> *Independent Research · Mentored by Dr. Prasanna Kolar @ SwRI*

MARLIN is a sub-$500 autonomous surface vehicle designed to detect and respond to drowning victims in real-time. I built it end-to-end — hardware CAD in Onshape, embedded firmware in MicroPython, and an ultralight computer vision pipeline running at **10 fps on an ESP32-S3 microcontroller**.

The model (FOMO-based, trained on a hand-labeled open-sourced dataset) achieves **95% recall** and **99% accuracy** on-device. I'm also building custom middleware analogous to ROS for the microcontroller-based architecture — sensor fusion across magnetometer, IMU, and GPS enables differential-thrust autonomous heading control.

Presented as a keynote at AJAS. Received IEEE & U.S. Navy Special Awards, and 1st Place in Engineering at both AJAS and ARSEF.

🔗 [GitHub](https://github.com/MiddleSender45/marlinv1) · [Research Poster](https://drive.google.com/file/d/1Ez2MAbrUNOZ2zwbKLqyyjG93jPQoKXpx/view?usp=gmail) · [Demo Video](https://www.youtube.com/watch?v=QcL_4hQYVng)

---

### 🪐 TRIPPY — Open-Source Planetary Rover
> *Software Lead · Trinity University · Dr. Kevin Nickels*

TRIPPY (Trinity Robotics Instructional Planetary Platform) is a Sawppy-variant rover that serves as an open-source research and education platform. I'm the software lead — responsible for the full autonomy stack.

The goal: patrol-and-detour navigation, where the rover can investigate detected anomalies while maintaining a global mission path. This means integrating Kinect RGB-D perception, YOLOv8 real-time object detection, and the full ROS 2 Nav2 pipeline.

I also architected the distributed networking for multi-machine ROS 2 communication (DDS discovery across subnets is genuinely painful), built the full Linux dev environment from scratch, and integrated simulated visual and LiDAR odometry into Nav2.

🔗 [GitHub](https://github.com/MiddleSender45/ros2_sawppy) · [Hackaday.io](https://hackaday.io/project/203634-trippy-a-sawppy-variant)

---

### 🦾 Alt-Bionics — VLA Models on Prosthetic Hands *(Upcoming)*
> *Robotics Research Intern · Mentored by Ryan Saavedra*

Implementing vision-language-action (VLA) models on robotic prosthetic hands to enable generalizable, context-aware grasping and manipulation — one of the more exciting intersections of embodied AI and assistive technology.

🔗 [altbionics.com](https://www.altbionics.com/)

---

## Side Builds

Outside of the primary research, I tinker:

- **Wispora** — A journaling app with an embedded Ollama LLM agent for task coordination and scheduling suggestions derived from journal entries.
- **Khord** — Custom Bluetooth adapter for simultaneous wired + wireless audio. PCB-level, firmware-up.
- **RC Aircraft** — Designed, built, and flew fixed-wing aircraft. Hands-on aerodynamics, motor control, and real-time stabilization electronics.

---

## Background

I come from a physics-heavy background — five 5s across AP Physics C (Mech + E&M), Physics 1 & 2, and Calculus BC. That foundation shapes how I think about systems: from torque and sensor noise to signal routing and control theory.

My technical range spans embedded firmware (MicroPython, C/C++), computer vision (FOMO, YOLOv8, Edge Impulse), robotics middleware (ROS 2, Nav2, DDS networking), hardware design (Onshape CAD, PCB integration), and full-stack Linux environments.

---

## This Repo

This is the source for my personal introduction site — a single-page portfolio styled as a PCB schematic. Built in vanilla HTML/CSS/JS with a PCB aesthetic: copper traces, silkscreen labels, via markers, and a live terminal typewriter effect. No frameworks, no build step, just `index.html`.

The design intentionally mirrors the way I think about systems — every element has a reference designator, every section is a layer.

---

*Open to research collaboration in robotics, autonomous systems, embedded ML, or maritime tech. Reach out.*
