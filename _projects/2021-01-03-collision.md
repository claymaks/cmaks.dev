---
layout: project
title: Point Simulation
description: Simulating points in a 2D Environment
summary: Simulating points in a 2D Environment
category: python, pygame, physics, algorithms
---

Swarm simulation environment using points in Pygame.

Simulation built to run with base `Point` agent.  Agent behavior can be altered 
by overriding or modifying the `update` method.

Multiple points moving towards center (with collisions)
<img src="/assets/img/pro/collisions/collisions.gif" alt="collisions"/>

One point moving towards center (calculated deceleration).
<img src="/assets/img/pro/collisions/one_point_center.gif" alt="collisions"/>

Multiple points moving towards center (no calculated deceleration).
<img src="/assets/img/pro/collisions/multi_point_no_decel.gif" alt="collisions"/>

All points moving towards center (calculated deceleration).
<img src="/assets/img/pro/collisions/all_center.gif" alt="collisions"/>

All points moving towards center (no calculated deceleration).
<img src="/assets/img/pro/collisions/all_no_decel.gif" alt="collisions"/>