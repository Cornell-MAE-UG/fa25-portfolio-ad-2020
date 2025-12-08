---
layout: project
title: ENGRD 2210 Otto Cycle / Internal Combustion Engine Analysis
description:
technologies: [None]
image: /assets/images/thermo1.png
---
## Introduction
The Otto cycle is a thermodynamic process used by spark ignition, two- or four-stroke internal combustion engines like those inside a car. It was patented by Alphonse Beau de Rochas in 1861, but the first successful four-stroke engine was built by Nicolaus Otto in 1876.
The cycle begins with an intake stroke. The intake valve is open and the piston moves down, drawing air and gasoline vapor into the engine. The intake valve closes and the piston moves up for the compression stroke. During the compression stroke, work is done on the gas by the system as the volume decreases and the pressure increases. During combustion, the mixture of fuel and air is heated very quickly, increasing the pressure and temperature (in an ideal model, the volume remains constant during this step). In an internal combustion engine, combustion is driven by the firing of the spark plug, which ignites the mixture inside the assembly. After combustion, the piston moves down in the power stroke. Volume increases and pressure decreases, and the gas does work on the system. After the power stroke, the exhaust valve opens: the pressure inside the assembly returns to the surrounding pressure and heat is exchanged with the surroundings at constant volume. The piston moves up during the exhaust stroke. Volume decreases and the pressure remains constant. From the exhaust stroke, the exhaust valve closes and the intake valve opens. The cycle starts over at the intake stroke.
![]({{ "/assets/images/otto-cycle-desc.png" | relative_url }})
*(original diagram: Piston and valves in a four-stroke internal combustion engine, Thermodynamics and Propulsion, Z. S. Spakovszky,* with added labels *)*

## The Otto Cycle on a P-V Diagram
![](/assets/images/otto-cycle-adiabatic.png)
*An ideal Otto cycle has two constant volume processes and two adiabatic, reversible processes. (diagram: Ideal Otto Cycle by NASA’s Glenn Research Center)*

![](/assets/images/otto-cycle-real.png)

*An actual Otto cycle has several irreversibilities, such as friction, and is not quasi-static.
(diagram: Sketch of an actual Otto cycle, Thermodynamics and Propulsion, Z. S. Spakovszky)*

## Efficiency
The efficiency of an Otto cycle is measured using the compression ratio, r, the ratio of volume at the beginning of the compression stroke to the volume at the end of the compression stroke. The efficiency of the cycle increases as r increases, but the temperature inside the piston also increases. Inside a real engine, the mixture will ignite at the wrong time if the temperature is too high (without the spark plug firing, outside of the combustion step). 
Otto cycle efficiency is measured using the equation 
$$
1 - \frac{1}{1^{\gamma-1}}
$$
*Efficiency of the Otto cycle.* r *is the compression ratio, and* γ *is the ratio of specific heats.*

![](/assets/images/otto-cycle-cr.png)

*Ideal Otto cycle efficiency vs. compression ratio,* r 
*(from Thermodynamics and Propulsion, Z. S. Spakovszky)*

## Power
The power produced by an engine using the Otto cycle is measured by multiplying the work done per cycle by the cycles per second, 
$$
P = W*cps
$$
Typical engines operate at a wide range of cycles per second. The cps depend on how fast a vehicle is going and what type of vehicle it is and can vary from hundreds to tens of thousands of cpm. Engine performance is typically measured in revolutions per minute, or rpm, which is 2x the cycles per second, since each revolution of the crankshaft and flywheel is ½ a cycle. A modern internal combustion engine inside a passenger car can operate at several thousand revolutions per minute. 

## Bibliography

Greitzer, E. M.; Spakovzsky, Z. S.; Waitz, I. A. “3.5 The Internal combustion engine (Otto 
Cycle),” https://web.mit.edu/16.unified/www/FALL/thermodynamics/notes/node26.html

“Four Stroke Engine,” *Animated Engines*, https://animatedengines.com/otto.html

“Ideal Otto Cycle p-V diagram,” *NASA Glenn Research Center*, https://www.grc.nasa.gov/www/k-12/airplane/otto.html

“Otto cycle,” *Wikipedia*, https://en.wikipedia.org/wiki/Otto_cycle

