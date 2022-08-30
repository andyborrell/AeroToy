# AeroToy - A 2D fluid simulator and physics sandbox

[![IMAGE ALT TEXT](https://andyborrell.github.io/aerotoy/aerotoy_0.1_thumbnail.jpg)](http://www.youtube.com/watch?v=3wV40Sn1hDY "AeroToy 0.1 beta Overview")



AeroToy is an interactive fluid simulator featuring two-way interaction between a semi-lagrangian real-time fluid simulation and a 2D rigid body physics simulation.

The purpose of AeroToy is not to provide accurate simulations for engineering purposes, but to provide accurate-enough interactive simulation to allow students or enthusiasts to experiment with the phenomena resulting from the interactions between subsonic aerodynamics and rigid bodies.

The fluid simulation is based on an algorithm ultimately derived from Stam Stable Fluids.  It is therefore optimized for real-time speed rather than accuracy, but has enough accuracy to recreate many of the phenomena arising from real fluid dynamics.  Some of the concepts that can be easily be explored include:

* High and low pressure regions generated by airflow around an airfoil and the lift thusly generated
* Relationship between angle of attack and lift/drag
* The affect of wing shape on lift/drag
* Vortex shedding from non-streamlined objects
* The Venturi effect
* The effect of center of mass position on aircraft stability
* The effect of elevator position on control authority
* Canard wings
* Aerodynamic stall


A key goal of AeroToy is that aerodynamics can be experimented with in real-time.  The AeroToy editor provides a fluid simulation running in parallel with the editor UI, meaning that as wing shapes are edited or painted, the effect on air flow can be seen immediately and interactively.

## Features
### Craft Editor
- Real-time fluid simulation during edit, providing real-time feedback
- Bezier wing editor
- Freehand wing paint tool
- Composition of rigid-body nodes from part nodes including Bezier curves and preconfigured parts such as engines
- Various simulation viewing modes including velocity and pressure
- Aerodynamic force vector and L/D annotation
- Library of predefined aircraft parts
- A collection of example scenes

### Flight Testing
- Keyboard controls for engines and control surfaces
- A library of test environments
- Configurable wind speed
- Airflow visualization tools
- Avionics summary including airspeed etc.
- Testing of fixed machines, such as windmills or kites, is also supported

## Download
Currently only a Windows binary build is available.   Download from the latest release from the [releases](https://github.com/andyborrell/AeroToy/releases) page.

## Tutorial
[![IMAGE ALT TEXT](https://andyborrell.github.io/aerotoy/aerotoy_0.1_tutorial_thumbnail.jpg)](http://www.youtube.com/watch?v=jSwZxcyRiAs "AeroToy 0.1 Tutorial")

## Source Code
Source code is not currently public. It might be in the future.
