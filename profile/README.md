# PACO Interceptor

Open-source software for an autonomous drone interceptor: guidance and control on a PX4 multirotor, and an on-board vision system that detects other drones in flight.

## Repositories

| Repository | What it does | Stack | License |
|---|---|---|---|
| [ws_interceptor](https://github.com/PACO-Interceptor/ws_interceptor) | ROS 2 workspace for target tracking and interception: proportional-navigation guidance, PX4 interface and Gazebo SITL simulation | ROS 2 Jazzy, PX4, C++ | Apache-2.0 |
| detector-drones *(moving to this organization)* | Air-to-air drone detector to run on board a Jetson Nano | Python, Ultralytics YOLO, TensorRT | AGPL-3.0 |

## Getting started

Clone the ROS 2 workspace and follow its README to build it and run the simulation:

```bash
git clone https://github.com/PACO-Interceptor/ws_interceptor.git
```

The step-by-step guide lives in the [ws_interceptor wiki](https://github.com/PACO-Interceptor/ws_interceptor/wiki).

## Contributing

Development is done by the project team. Issues and pull requests can only be opened by team members, but questions, ideas and advice are welcome:

- Use **Discussions** in the relevant repository.
- Comment on existing issues and pull requests.

To report a security problem, please don't use a public discussion: contact the maintainers privately.
