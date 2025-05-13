---
layout: project
title: Fractal Generator
description: Computer Graphics Project
technologies: [Golang]
image: /assets/images/tet.png
---

For fun, I wanted to make a program to generate fractals. My language of choice at the time was Golang, so I set out to code one up. This program can generate fractals if given functions to iterate about the complex plane. Here's a fractal generated from iterating the Binet Formula for Fibonacci Numbers:

![Binet Fractal]({{ "/assets/images/bin.png" | relative_url }}){: .inline-image-r style="width: 200px"}

The program also supports drawing attractors. These are formed by evolving systems of two differential equations and tracking the trajectory of a point that moves according to those equations. With carefully picked equations, we can make a donut:

![Svennson Attractor]({{ "/assets/images/don.png" | relative_url }}){: .inline-image-r style="width: 200px"}