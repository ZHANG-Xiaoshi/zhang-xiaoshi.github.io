---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* M.Sc. at National University of Singapore, Master of Science (2022.08-2023.12)
  * Major：Mechanical Engineering,
  * GPA：4.83/5
  * Core Courses：Neural Networks, Deep Learning for Robotics, Linear Systems(A), Engineering Acoustics(A)
* Joint education program at NUS (Suzhou) Research Institute (2021.09 - 2022.07)
  * Major：Mechanical Engineering,
  * GPA：89.3/100
* B.Eng. at Harbin Institute of Technology (2018.08-2021.07)
  * Major：Mechanical Engineering,
  * GPA：86.9/100



Research and Work Experience
======
* 2022.11 - Now: Reinforcement learning for tactile-based manipulation control
  * Research Internship at The Agency for Science, Technology, and Research (A*STAR) of Singapore
  * Research objective: To solve the ”peg in hole assembly” task with tactile feedback
  * Supervisors: Prof. Chew Chee Meng, Dr.Wu Yan 


* 2021.09 - 2022.06: Deep reinforcement learning for double inverted pendulum control
  * Final year project at NUS (Suzhou) Research Institute
  * Research objective: To study the application of RL algorithms in continuous control problems
  * Supervisor: Prof. Chew Chee Meng
  * Contributions:
    * (1)Proposed neural network controllers for double inverted pendulum stabilizing, swinging up, and limit cycle
control using deep reinforcement learning algorithms(DDPG and TD3).
    * (2)Reduced the steady-state error in the stabilization control and improved the disturbance immunity by optimizing the reward function and the environment.
    * (3)Proposed a control framework combining RL with state feedback control.
    * 4)Validated control performance using Simulink and Simscape.
  * This work is accepted by The 5th International Conference on Machine Learning and Machine Intelligence
(ACM Conference), however we are searching for better conferences to publish.

* 2021.03 - 2021.06: Modeling and motion simulation of a tensegrity snake-like robot
  * Research Internship at Harbin Institute of Technology
  * Research objective: To study the application of RL algorithms in continuous control problems
  * Supervisor: Prof. He Jingfeng
  * Contributions:
    * (1)Proposed a snake-like robot driven by actuating cables on the both sides based on tensegrity structure.
    * (2)Studied inverse kinematics based on the serpenoid curve.
    * (3)Verified control feasibility using ADAMS-Simulink co-simulation.
  * Published on Journal of Physics: Conference Series. Vol. 1965. No. 1. IOP Publishing, 2021.(EI Compendex).

Skills
======
* English skills: IELTS 7.0()
* Programming Skills: C/C++, Python, Matlab
* Proficient Softwares:
  * Mechanical Designing and FEM: Solidworks, AutoCAD, ANSYS, Abaqus,
  * Dynamics Simulation with contacts: ADAMS,Matlab Simulink, ADAMS-Simulink Co-simulation
  * Reinforcement Learning: Matlab RL Toolbox, Pytorch
  * Robotics: ROS
* Others: Microsoft Office, LaTeX
  
Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Research Interest
======
* Reinforcement Learning
* Robotics
* Dexterous Manipulation

