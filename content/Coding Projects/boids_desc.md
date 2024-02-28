---
title: Boids
tags:
  - coding
---

## What is it?

Boids is an artifical life program developed by Craig Reynolds in 1980 and
has been used in lots of different games and applications to simulate
flocking behavior. It is based on three principles: **coherence** (steering
towards the center of mass of a flock), **separation** (avoid colliding
with other boids in the flock), and **alignment** (steer towards the
average heading of the other flockmates). These three simple principles
lead to pseudorealistic flocking behavior that is easily simulated. This
kind of behavior can be used to simulate, birds, fish, insects, or other
kinds of herds.

## This version

This is my take on it written in Rust using macroquad and egui.
You can [[boids.html|view the HTML file]], get the compiled WASM binary [[boids.wasm|get the compiled WASM binary]], and
[check out the repository](https://github.com/SiddhantDeshmukh/boids).

## Demo

This demo runs best on desktops and gives a feel for the simulation along with a few parameters to tweak.

<div align="center">
    <iframe width="640px" min-width="640px" max-width="1920px"
            height="500px" min-height="480px" max-height="1080px"
            src="boids.html">
    </iframe>
</div>
