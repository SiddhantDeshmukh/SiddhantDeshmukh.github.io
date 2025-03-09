---
title: Particle Life
tags:
  - coding
---

## What is it?

Particle Life is an emergent complexity simulation similar to
[[https://www.conwaylife.com|Conway's Game of Life]]. Through simple interactions between particles
(based on their colour), a beautiful sea of "life" emerges. The rules of the simulation are similar to
an n-body and determined by color-color relations. While in a traditional n-body simulation (like a
gravitational one) the forces are symmetric (body A exerts an equal and opposite force on body B), the forces
in a particle life simulation are asymmetric (blue particle can exert a different force on orange particle
compared to orange on blue). This leads to certain colours bunching up, other colours being repelled, and a
constantly evolving, visually appealing landscape. Part of the fun in this simulation is seeing larger
structures forming and acting like creatures, when in fact there are just a few simple rules behind the scenes.

## This version

This is my take on it written in Rust using macroquad and egui (I initially wrote it with raylib but found UI elements difficult to code).
You can [[particle_life.html|view the HTML file]], get the compiled WASM binary [[particle-life.wasm|get the compiled WASM binary]], and
[check out the repository](https://github.com/SiddhantDeshmukh/particle_life).

## Demo

This demo runs best on desktops and gives a feel for the simulation along with a few parameters to tweak.

<div align="center">
    <iframe width="640px" min-width="640px" max-width="1920px"
            height="500px" min-height="480px" max-height="1080px"
            src="pl_embed.html">
    </iframe>
</div>
