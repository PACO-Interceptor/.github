# PACO Interceptor

Software for a drone that intercepts other drones. It flies on PX4 with a companion computer running ROS 2.

The project website, with the concept of operations, requirements, subsystems and test plan, is at **[paco-interceptor.github.io](https://paco-interceptor.github.io)**.

## Repositories

- **[ws_interceptor](https://github.com/PACO-Interceptor/ws_interceptor)**: ROS 2 Jazzy workspace with the guidance and control nodes (proportional navigation) and the PX4 SITL + Gazebo setup we use for testing. Apache-2.0.
- **detector-drones**: YOLO model that detects drones from the air, meant to run on a Jetson Nano. AGPL-3.0. We're still moving it to this organization.
- **[PACO-Interceptor.github.io](https://github.com/PACO-Interceptor/PACO-Interceptor.github.io)**: source of the project website, built with VitePress.

## Trying it out

Start with the [ws_interceptor README](https://github.com/PACO-Interceptor/ws_interceptor#readme). The [wiki](https://github.com/PACO-Interceptor/ws_interceptor/wiki) explains how to build the workspace and run the simulation.

## Getting in touch

Only team members can open issues and pull requests, but comments and Discussions are open to everyone, so feel free to leave suggestions there. If you find a security problem, please don't post the details publicly; ask for a private contact in a Discussion.
