---
layout: archive
title: "Legged Robots with Serpentine Tails"
permalink: /research/legged-robot-with-tail
author_profile: true
header:
  og_image: "images/rcqt.jpg"
---

Our research path on this direction mainly consists of two branches: one theoretical branch that focuses on using dynamics and control theory to understand the tail-involved legged locomotion problem, and one empirical branch that focuses on developing legged robots with a serpentine robotic tail and using hardware to practically verify the theoretical findings. We have proposed that with a serpentine robotic tail onboard, the legged robot may be able to perform some unique functionalities.

<img style="height:300px;" src="/images/bioinspiration.jpg"/>

At present, on the theoretical side, we have created general dynamic models for both the quadruped and biped cases, with either an articulated tail or a continuum tail. We have also developed motion controllers based on the classical feedback linearization-based control and the numerical optimal control, to coordinate the leg motion and the tail motion. Some of the simulations are shown here.

For bipedalism (using a kangaroo rat model as an example), a serpentine tail is controlled to help the kangaroo rat to adjust its airborne posture, stabilize its locomotion through environmental contacts, and recover itself from falling.

<p float="left">
  <img style="height:270px;" src="/images/kr-at-ar-sim.gif"/>
  <img style="height:270px;" src="/images/kr-at-ar-optSim.gif"/>
  <img style="height:270px;" src="/images/kr-at-ar-2s-opt.gif"/>
  <img style="height:270px;" src="/images/kr-at-ar-3s-opt.gif"/>
</p>

For quadrupedalism (using a reduced complexity quadruped robot VT Lemur as an example), a serpentine tail is controlled to help the quadruped robot to change its heading direction (yaw maneuvering) and to assist its locomotion through environmental contacts.

<p float="left">
  <img style="height:180px;" src="/images/rcqt-maneuver-sim.gif"/>
  <img style="height:180px;" src="/images/rcqt-standup-sim.gif"/>
  <img style="height:180px;" src="/images/rcqt-balance.gif"/>
  <img style="height:180px;" src="/images/rcqt-recovery.gif"/>
</p>

On the empirical side, we have also developed several hardwares, including robotic tails (see the [RML Tail](/research/rmltail) and the [Rigitail](/research/rigitail)) and quadruped robots. Here shows one reduced complexity quadruped robot (RCQ robot for short) before integrating a robotic tail,

<p float="left">
  <img style="height:200px;" src="/images/rcq-slomo.gif"/>
</p>

and the VT Lemur robot with the Roll-Revolute-Revolute Robotic Tail (a.k.a. R3RT) integrated onboard.

<p float="left">
  <img style="height:200px;" src="/images/vt-lemur.jpg"/>
  <img style="height:200px;" src="/images/vt-lemur-man.gif"/>
  <img style="height:200px;" src="/images/rcqt-standup.gif"/>
</p>

**Related Publications:**

**Liu, Y.** and Ben-Tzvi, P., 2023, "How a Serpentine Tail Assists Agile Motions of Kangaroo Rats: A Dynamics and Control Approach", Nonlinear Dynamics, 111(16), pp. 14783-14803. [<img style="height:15px;" src="/images/link.png"/>](https://link.springer.com/article/10.1007/s11071-023-08646-w)

Pressgrove, I., **Liu, Y.** and Ben-Tzvi, P., "Design and Implementation of a Power-Dense, Modular, and Compact Serpentine Articulated Robotic Tail", Proceedings of the ASME 2022 International Design Engineering Technical Conferences and Computers and Information in Engineering Conference (IDETC/CIE2022), 46th Mechanisms & Robotics Conference, St. Louis, MO, USA, August 14-17, 2022, p. V007T07A053.  [<img style="height:15px;" src="/images/link.png"/>](https://asmedigitalcollection.asme.org/IDETC-CIE/proceedings-abstract/IDETC-CIE2022/V007T07A053/1150683)

**Liu, Y.** and Ben-Tzvi, P., "Systematic Development of a Novel, Dynamic, Reduced Complexity Quadruped Robot Platform for Robotic Tail Research", 2022 IEEE International Conference on Robotics and Automation (ICRA), Philadelphia, PA, USA, May 23-27, 2022, pp. 4664-4670.  [<img style="height:15px;" src="/images/link.png"/>](https://ieeexplore.ieee.org/abstract/document/9811871)

Ben-Tzvi, P. and **Liu, Y.**, 2021, "Robots With Tails", ASME Mechanical Engineering Magazine, 143(6), pp. 32-37. [Magazine Article]  [<img style="height:15px;" src="/images/link.png"/>](https://asmedigitalcollection.asme.org/memagazineselect/article/143/6/32/1129192/Robots-with-TailsFour-legged-Robots-are-Now)

**Liu, Y.** and Ben-Tzvi, P., "Feedback Control of the Locomotion of a Tailed Quadruped Robot", Proceedings of the ASME 2021 International Design Engineering Technical Conferences and Computers and Information in Engineering Conference (IDETC/CIE2021), 45th Mechanisms & Robotics Conference, Virtual, Online, Aug. 17-20, 2021, p. V08BT08A009.  [<img style="height:15px;" src="/images/link.png"/>](https://asmedigitalcollection.asme.org/IDETC-CIE/proceedings-abstract/IDETC-CIE2021/85451/V08BT08A009/1128376)

**Liu, Y.** and Ben-Tzvi, P., 2021, "Dynamic Modeling, Analysis, and Design Synthesis of a Reduced Complexity Quadruped with a Serpentine Robotic Tail", Integrative and Comparative Biology, 61(2), pp. 464–477.  [<img style="height:15px;" src="/images/link.png"/>](https://academic.oup.com/icb/article/61/2/464/6276989?login=true)

**Liu, Y.** and Ben-Tzvi, P., 2021, "Dynamic Modeling, Analysis, and Comparative Study of a Quadruped with Bio-inspired Robotic Tails", Multibody System Dynamics, 51(2), pp. 195-219.  [<img style="height:15px;" src="/images/link.png"/>](https://link.springer.com/article/10.1007/s11044-020-09764-8)

**Liu, Y.** and Ben-Tzvi, P., 2020, "An Articulated Closed Kinematic Chain Planar Robotic Leg for High Speed Locomotion", Journal of Mechanisms and Robotics, Transactions of the ASME, 12(4), p. 041003.  [<img style="height:15px;" src="/images/link.png"/>](https://asmedigitalcollection.asme.org/mechanismsrobotics/article-abstract/12/4/041003/1071947/An-Articulated-Closed-Kinematic-Chain-Planar?redirectedFrom=fulltext)

Rone, W., **Liu, Y.** and Ben-Tzvi, P., 2019, "Maneuvering and Stabilization Control of a Bipedal Robot with a Universal-Spatial Robotic Tail", Bioinspiration & Biomimetics, 14(1), p. 016014.  [<img style="height:15px;" src="/images/link.png"/>](https://iopscience.iop.org/article/10.1088/1748-3190/aaf188)

**Liu, Y.** and Ben-Tzvi, P., "Dynamic Modeling of the Quadruped with a Robotic Tail Using Virtual Work Principle", Proceedings of the ASME 2018 International Design Engineering Technical Conferences and Computers and Information in Engineering Conference (IDETC/CIE2018), 42nd Mechanisms & Robotics Conference, Quebec City, Canada, Aug. 26-29, 2018, p. V05BT07A021.  [<img style="height:15px;" src="/images/link.png"/>](https://asmedigitalcollection.asme.org/IDETC-CIE/proceedings-abstract/IDETC-CIE2018/51814/V05BT07A021/276123)
