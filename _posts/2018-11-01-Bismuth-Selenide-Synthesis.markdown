---
layout: post
title: "Bismuth Selenide Synthesis: Taufour Lab"
description:
image: /assets/images/Topological_Insulator_Bi2Se3.png
author: Ian Phillips
tags:
  - Projects
  - Blog
  - Materials
---

Recently, research of the compound __Bi<sub>2</sub>Se<sub>3</sub>__, known as Bismuth Selenide, has exploded in the Material Science community. This is due to its interesting properties and unique behavior.

Bismuth Selenide is a __topological insulator__, meaning it functions as an insulator within its bulk, or interior, but has better than average conduction on its surface, about 3 nanometers deep. Why?

Normally, when electrons flow through a material, some are backscattered by defects in the structure, causing resistance. On the surface of a topological insulators however, the electrons flow only in the direction of their spin (positive or negative), and therefore cause less resistance. When an electron encounters a defect, its spin is altered to be the exact opposite. Consider the surface of a TI to be like a highway, and when there is a bump in the road, a car takes a U-turn, without effecting traffic on the side it was originally on.

In Taufour Lab, we are attempting to grow single crystal Bismuth Selenide using the __Bridgman technique__.

<img style="float: right" alt="Source: https://guedel.dcb.unibe.ch/research/hug_cry_movie.htm" src="/assets/images/Bridgman.gif"/> This technique uses a sealed ampoule, evacuated of air, with the Bismuth and Selenium finely ground and mixed by hand. This tube is slowly lowered vertically through a __temperature gradient__, in this case formed by two furnaces insulated and stacked together.
The highest temperature reached is the melt homogenization temperature, much higher than the melting point of the compound. This ensures best mixing of Bismuth and Selenium, in turn reducing defects. Using a servo motor controlled by a raspberry pi, the sample is lowered at a rate in the realm of mm/hr.

This method allows for a single crystal to form and slowly build until the entire sample is one grain. __Excess Selenium and Calcium__ doping are the next steps in forming a perfect topological insulator.

<sub>References: https://www.tum.de/en/studies/studinews/issue-022016/show/article/32312/
