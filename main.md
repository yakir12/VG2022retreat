---
marp: true
title: DancingQueen
description: Vision Group retreat 2022 presentation
author: Yakir Gagnon
theme: uncover
headingDivider: 1
paginate: false
---

# Building the DancingQueen
VG Spring Outing 2022
Yakir Gagnon

# 

<!-- _backgroundColor: black -->

<video controls object-fit: fill >
    <source src="https://vision-group-temporary.s3.eu-central-1.amazonaws.com/dance.webm" type="video/webm">
    <source src="https://vision-group-temporary.s3.eu-central-1.amazonaws.com/dance.mp4" type="video/mp4">
    <source src="https://vision-group-temporary.s3.eu-central-1.amazonaws.com/dance.ogv" type="video/ogv">
    Sorry, your browser doesn't support embedded videos.
</video>

<!-- Dung beetles scan their environment before rolling -->
<!-- This scan is performed by "dancing" on the dungball -->
<!-- They climb the dungball, rotate on top of it, descend from the ball, and roll it -->
<!-- The sun is one of the main cues influencing their choice -->

# The DancingQueen experiment
**Q**: *How important is the sun for the beetle's choice of direction?*

<div data-marpit-fragment>
A closed-loop control-system where the location of an ersatz sun changes as a function of the beetle's orientation
</div>

<!-- A closed loop control system where we update the location of an ersatz sun as a function of the beetle's orientation -->

# The experimental setup
- The dung beetle is placed on a dungball in the center of a small arena
* Around the arena is a circle of LEDs
* One turned-on LED simulates the sun
* The location of the "sun" depends on the beetle's orientation
* The orientation is auto-detected from an Apriltag glued to the beetle's back

# Fun things to try
- Does setting the sun's location to the beetle's orientation extend the dance?
* Does adding noise to the location of the sun diminish the directional accuracy?
* Will the beetle rather use a dimmer yet stable sun over a bright and noisy one?

# Questions?
