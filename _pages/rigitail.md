---
layout: archive
title: "A 2DOF Robotic Tail Using Rigid Link Transmission"
permalink: /research/rigitail
author_profile: true
header:
  og_image: "images/rigitail-intro.jpg"
---

Based on observations from nature, tails are believed to help animals achieve highly agile motions. Traditional single-link robotic tails serve as a good simplification for both modeling and implementation purposes. However, this approach cannot explain the complicated tail behaviors exhibited in nature where multi-link structures are more commonly observed. Unlike its single-link counterpart, articulated multi-link tails essentially belong to the serial manipulator family which possesses special motion transmission design challenges. To address this challenge, a cable-driven hyper-redundant design becomes the most used approach. Limited by cable strength and elastic components, this approach suffers from low-frequency response, inadequate generated inertial loading, and fragile hardware, which are all critical drawbacks for robotic tails design. To solve these structure-related shortcomings, a multi-link robotic tail made up of rigid links is proposed in this paper. The new structure takes advantage of the traditional hybrid mechanism architecture, but utilizes rigid mechanisms to couple the motions between the ith link and the (i + 1)th link rather than using cable actuation. By doing so, the overall tail becomes a rigid mechanism that achieves quasi-uniform spatial bending for each segment and allows performing highly dynamic motions. The mechanism and detailed design of this new robotic tail are presented. The kinematic model was developed and an optimization process was conducted to reduce the bending non-uniformity for the rigid tail. Based on this special optimization design, the dynamic model of the new mechanism is significantly simplified. A small-scale three-segment prototype was integrated to verify the proposed mechanism's unique mobility.

An animation shows the mechanism principle: 

<img style="height:300px;" src="/images/rigitail.gif"/>

A proof-of-concept prototype:

<img style="height:200px;" src="/images/rigitail.jpg"/>
