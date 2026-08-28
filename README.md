# inverted_Pendulum

A fully custom designed cart and pole inverted pendulum as a mini project to explore Control Theory and Reinforcement Learning on a more deep level to hopefully implement into an autonomous bike 

This project is a classic engineering problem where the center of mass of the pendulum is above the pivot point making it an inhenrently unstable system unless an active control system keeps it upright, in this case a cart and pole system.

<img src="https://github.com/user-attachments/assets/1b71f869-0904-4f14-a556-56bcd60dfa13" width="600">


> **Current status:** V1 of the mechanical side is done and is printed out, but I got a new motor so v2 is done on CAD but still needs to be printed out. I also vibe-coded a PID version of the balancing which runs 2 PID loops one for the balancing and another to keep the car near the middle of the track.
---

# build overview

The system is powered by a Flyroun 5008 KV340 Brushless Motor running on FOC with a belt drive that attaches to the cart. On the cart is the housing that holds the pendulum as well as the encoder that tracks the position and angular velocity and acceleration of the pendulum.

- 3D Printed with PLA

- linear bearings for the card sliding

- steel linear rods holds the cart

- m3s m4s, and heated inserts for putting everything together

- Flyroun 5008 KV340 Brushless Motor

- Makerbase MKS XRIVE MINI FOC Controller

- Carbon Fiber Rod as the pendulum

---

# prog

so this projects main objective was for me to explore and learn more advanced control theory and programming through exploring more sophisticated control methods like and reinforcement learning. So with the help of another maker named "zjor" on github who was kind enough to open source his code for an inverted pendulum, and AI I made a simulation in python so I can do most of the testing on here before worrying about electronics and hardware getting in the way.

<img width="400" height="338" alt="Screen Recording 2026-08-27 at 9 39 07 PM" src="https://github.com/user-attachments/assets/b85cc78f-b0fe-499c-9049-3ab55c1dbd16" />

Currently this is running 2 PID loops one to keep the cart near the middle of the track and then another to keep the pendulum up, and in the future I plan to implement LQR and RL





# make sure to check media.md and build_logs.md for updates

:D

in progress...



