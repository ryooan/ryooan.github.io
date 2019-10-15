---
layout: post
author: Ryan
title: Robots and Rubik's Cubes
tags: [science]
---
This is some really cool stuff. A group called Open AI has used machine learning to teach a robotic hand to solve a Rubik's cube. They trained the hand to overcome a variety of interferences with its mechanics as well, such as having some of its fingers tied or having a stuffed giraffe try to move the cube around.

According to their article it can solve a Rubik's cube 60% of the time, and it can solve a Rubik's cube starting at the maximum number of moves from completion (26) 20% of the time. If it drops the cube or times out it's considered a failure. The movements aren't programmed in directly, they trained the hand using a simulated model of the hand so that they could do thousands and thousands of iterations under a variety of random environments (different cube sizes, parts of the hand disabled, different finger friction, etc.). Then they applied the resulting program to the actual mechanical hand.

It's pretty amazing how much movement this hand has and how it adapts to the "perturbations" they apply. They can randomize a Rubik's cube and place it in the hand and it'll work out how to solve it. Check out their article about it for more information, it's really fascinating and I definitely recommend checking out the part about the perturbations, the videos of that are really cool: [https://openai.com/blog/solving-rubiks-cube/](https://openai.com/blog/solving-rubiks-cube/)

<div class="embedvideodiv">
<iframe class="embediframe" src="https://www.youtube.com/embed/kVmp0uGtShk" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>