<h1>Hi, I'm Khanh!<br/>
<a href="https://github.com/khanhphan511">Electrical Engineering Student</a>, 
<a>Vision & Automation Enthusiast</a>, 
<a>Robotics / Autonomous Vehicle Developer</a>
</h1>

🎓 I’m an Electrical Engineering student at Oakland University (graduating December 2025) focused on:
- Scale autonomous vehicles (ride-on car → IGVC-style platform)
- Machine vision & LiDAR-based obstacle detection
- CAN-based motor control, embedded systems, and electric machines

---

<h2>🤖 Robotics & Autonomous Vehicle Projects</h2>

- <b>Scale Autonomous Vehicle – Vision & Automation (ROS 2, 4D LiDAR, Depth Camera)</b>  
  - ROS 2 Humble stack on Ubuntu 22.04 for a ride-on-car–based autonomous vehicle  
  - OAK-D depth camera + 4D LiDAR for lane detection and obstacle ranging  
  - Python nodes to compute lane offset / obstacle distance and publish steering & speed commands to Arduino-based motor controllers  
  - ROS 2 drive-state debug indicators (Forward/Stop/Left/Right) and camera overlays to tune thresholds and control responses  
  - Migrated ROS 2 workspace from laptop virtual machine to Jetson Orin Nano for fully onboard autonomy  
  - Focus on headless startup and robust deployment for IGVC-style field tests
  - Repo: [scale-autonomous-vehicle-ros2](https://github.com/khanhphan511/scale-autonomous-vehicle-ros2)

  
- <b>Pixy2 ADAS Robotic Car (Active Cruise, Traffic Light, Lane Keeping)</b>  
  - Small differential-drive car with Pixy2 vision sensor and Arduino  
  - Implemented object following with safety distance, traffic-light timing logic, time-to-pass decision, and lane keeping  
  - Repo: [pixy2-adas-robot-car](https://github.com/khanhphan511/pixy2-adas-robot-car)

- <b>Playdough Rose Automation (ABB IRB 120 Industrial Robot)</b>  
  - Programmed an ABB IRB 120 six-axis industrial robot using the FlexPendant and RAPID language to perform precision path-planning tasks  
  - Developed and tested Cartesian and joint-space trajectories to cut a playdough strawberry into a rose and place it into a vase while maintaining smooth, collision-free motion  
  - Demo video: [Playdough Rose Automation](https://youtube.com/shorts/Cg1ANpr1HYg?feature=share)
---

<h2>🚗 Embedded Control & CAN Projects</h2>

- <b>Adaptive Cruise Control & Forward Collision Avoidance using CAN</b>  
  - Built a two-node CAN network with Arduino + MCP2515 controllers  
  - IR distance sensor node sends measurements via CAN frames to a motor-control node  
  - Arduino C/C++ firmware adjusts motor PWM for speed control and braking at configurable stop thresholds  
  - Repo: [can-adaptive-cruise-bench](https://github.com/khanhphan511/can-adaptive-cruise-bench)


---

<h2>⚡ Electric Machines & Power Projects</h2>

- <b>SynRM / PMSynRM / IPMSM Design & Analysis (PEEC Lab)</b>  
  - Designed SynRM, PMSynRM and IPMSM geometries in Ansys Maxwell  
  - Evaluated torque, losses, and saliency ratio for EV-style drives  
  - Built MATLAB workflows to post-process large FEA datasets and compare physics-informed neural networks to FEA  

---

<h2>🛠️ Tech Stack</h2>

- <b>Robotics & Embedded</b>: ROS 2 Humble, Arduino, Jetson Orin Nano, OAK-D depth camera, 4D LiDAR, ABB IRP 120  
- <b>Programming</b>: Python, C, C++, VHDL, basic Java & Visual Basic  
- <b>Simulation & Design</b>: MATLAB/Simulink, Ansys Maxwell, JMAG, RT LAB, LTspice, PSpice, AutoCAD, Siemens NX  
- <b>Testing & Debugging</b>: Oscilloscope, multimeter, soldering, hardware bring-up, structured troubleshooting

---

<h2>📚 What I’m Learning Now</h2>

- Advanced ROS 2 (better node structuring, launch files, and debugging)
- More robust vision pipelines for lane detection and obstacle avoidance
- Best practices for deploying autonomous systems on embedded platforms (Jetson, microcontrollers)
- Industrial vision automation concepts for manufacturing environments




<!--
**<your-username>/<your-username>** is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Ideas to keep this updated:
- 🔭 I’m currently working on: scale autonomous vehicle + CAN bench
- 🌱 I’m currently learning: ROS 2, Jetson deployment, vision automation
- 👯 I’m looking to collaborate on: robotics, autonomous vehicles, electric machines
- 💬 Ask me about: ROS 2 basics, Arduino motor control, student research in electric machines
-->
