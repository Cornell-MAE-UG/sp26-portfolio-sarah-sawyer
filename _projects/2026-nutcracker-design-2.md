---
layout: project
title: Nutcracker Design 2
technologies: n/a
description: A nutcracker I designed for my Statics class, revisited.
image: /assets/images/nutcracker-design-2.jpg
---


The objective of this project was to modify the design of a nutcracker capable of cracking open a macadamia nut with a linear actuator and non-rigid handles.

The handles can be described as beams that bend due to the combined action of the forces from the nut and the actuator. The goals of this problem were to find the location of maximum elastic deflection in the handles, then choose and draw a beam design (cross section and material) so that the vertical elastic deflection is below 2% of its length and is the most mass-efficient possible.

Based on the original nutcracker designed I established, the handle length was 363.5 mm, the length from the hinge to the jaw is 51.92 mm, and the force of the linear actuator is 175 N.

It was assumed that each handle could be simply modeled asw a beam pinned at one end and with a roller at the other (the linear actuator). It was also assumed that the loading comes from a force from the nut at the jaws.

First, the location of maximum elastic deformation was calculated using the formula provided for Beam 5 in Appendix E. This resulted in a distance to maximum deformation of 207.7 mm from the hinge. By taking the moment about A, the force of the nut was calculated as -1225 N.

<img src="{{ site.baseurl }}/assets/images/nutcracker-work-1.jpg" width="600" />

 Then the equation for maximum deformation was used from Appendix E to find an inequality for EI. By selecting structural steel as the material to make E=200 GPa, it was determined that the moment of iner*tia had to be greater tha 3.597*10^-10. The equation for I=(1/12)bh^3 was used to find h given b=0.005 m. h was determined to have to be at leasst 0.00952 m, so 10 mm was selected to be safe.

<img src="{{ site.baseurl }}/assets/images/nutcracker-work-2.jpg" width="600" />

Therefore, the nutcracker was designed to be made of structural steel, with a cross section of b=5mm and h=10 mm.

Here is a diagram of my new nutcracker design.
<img src="{{ site.baseurl }}/assets/images/nutcracker-design-2.jpg" width="600" />\

These dimensions feel reasonable and achievable. Structural steel is an affordable, stiff, and durable material, making it a good choice for the design.