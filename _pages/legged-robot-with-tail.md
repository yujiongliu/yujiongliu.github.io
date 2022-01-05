---
layout: archive
title: "Legged Robots with Serpentine Tails"
permalink: /research/legged-robot-with-tail
author_profile: true
header:
  og_image: "images/rcqt.jpg"
---

Our research path on this direction mainly consists of two branches: one theoritical branch that focuses on using dynamics and control theory to understand the tail-involved legged locomotion problem, and one empirical branch that focuses on developing legged robots with a serpentine robotic tail and using hardware to practically verify the theoritical findings. We have proposed that with a serpentine robotic tail onboard, the legged robot may be able to perform some unique functionalities.

<img style="height:300px;" src="/images/bioinspiration.jpg"/>

At present, on the theoritical side, we have created general dynamic models for both the quadruped and biped case, with either an articulated tail or a continuum tail. We have also developed motion controllers based on the classical feedback linearization-based control and the numerical optimal control, to coordinate the leg motion and the tail motion. Some of the simulations are shown here.

For bipedalism (using a kangaroo rat model as example), a serpentine tail is controlled to help the kangaroo rat to adjust its airborne posture, stabilize its locomotion through environmental contacts, and recover itself from falling.

<p float="left">
  <img style="height:270px;" src="/images/kr-at-ar-sim.gif"/>
  <img style="height:270px;" src="/images/kr-at-ar-optSim.gif"/>
  <img style="height:270px;" src="/images/kr-at-ar-2s-opt.gif"/>
  <img style="height:270px;" src="/images/kr-at-ar-3s-opt.gif"/>
</p>

<p float="left">
  <img style="height:200px;" src="/images/kr-at-jp-nt.gif"/>
  <img style="height:200px;" src="/images/kr-at-jp-wt.gif"/>
  <img style="height:200px;" src="/images/kr-ct-sr.gif"/>
</p>

For quadrupedalism (using a reduced complexity quadruped robot RCQt as example), a serpentine tail is controlled to help the quadruped robot to adjust its airborne posture and change its heading direction (maneuvering).

<p float="left">
  <img style="height:200px;" src="/images/rcq-ar-nt.gif"/>
  <img style="height:200px;" src="/images/rcq-ar-wt.gif"/>
  <img style="height:200px;" src="/images/rcq-mn.gif"/>
</p>

On the empirical side, we have also developed several hardwares, including robotic tails (see the [RML Tail](/research/rmltail) and the [Rigitail](/research/rigitail)) and quadruped robots. Here shows one quadruped prototype and one concept design for the tailed quadruped robot.

<p float="left">
  <img style="height:300px;" src="/images/rcq-slomo.gif"/>
  <img style="height:300px;" src="/images/rcqt.jpg"/>
</p>
