# Simulation

This folder contains the simulation work for the SIH UGV Autonomous Navigation project.

## Current Progress

A basic Webots simulation has been created using the e-puck robot.

The current prototype demonstrates:

- Robot movement in the Webots environment
- Grid-based path planning using A*
- Following a sequence of planned grid coordinates
- Basic turning and forward movement
- A defined simulation arena

## Current Status

The current implementation is an initial prototype for understanding robot navigation and path planning.

The next stages will focus on:

- Adding static obstacles to the environment
- Updating the planner to avoid obstacles
- Testing Hybrid A* for realistic rover motion
- Adding perception-based traversability information
- Integrating localization and control modules

## Tools

- Webots
- Python
- A* Path Planning

This simulation will gradually evolve toward a GPS-denied autonomous UGV navigation system.
