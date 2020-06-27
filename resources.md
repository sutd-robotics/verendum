# Resources

Here are some compilation of the various software, packages and tools to assist you while exploring the realms of robotics. Enjoy!  🍾



## Editor

### Documentation

- **Typora**: A markdown language text editor, which comes really handy when documentation is needed.
- [Markdown Table of Content (ToC) Adder](https://github.com/methylDragon/markdown-linked-toc-adder): Add a linked Table of Contents to any GitHub flavoured Markdown file!
- [Fritzing](https://github.com/fritzing/fritzing-app/releases): A software tool to create and design your electronic projects, especially useful when one wants to create a schematic or breadboard view of the project.
- [WireViz](https://github.com/formatc1702/WireViz): A tool for easily documenting cables, wiring harnesses and  connector pinouts. It takes plain text, YAML-formatted files as input  and produces beautiful graphical output (SVG, PNG, ...) thanks to [GraphViz](https://www.graphviz.org/). It handles automatic BOM (Bill of Materials) creation and has a lot of extra features.



### Coding

### Terminal based

- **vim**: Even if it may be intimidating to have no GUI and learn all the various in this terminal base text editor, it sure pays off when only cli (command line interface) is available. Could be accessed via `$ vim` 

> You can learn vim via *vimtutor*, run `$ vimtutor ` through the terminal in Ubuntu.

- **nano**: A terminal base text editor, comes preinstalled in [Xubuntu](https://xubuntu.org/)(Ubuntu that uses the Xcfe desktop instead).

### Graphical User Interface (GUI)

- [gedit](https://wiki.gnome.org/Apps/Gedit): Comes preinstalled with Ubuntu.
- **[VS Code](https://code.visualstudio.com/)**: Open Source Code Editor.



## Learning

- [Coding Notes](https://github.com/methylDragon/coding-notes)



## Simulators

- [Gazebo](http://gazebosim.org/): Open source robotics simulator.

- [AirSim](https://github.com/Microsoft/AirSim): AirSim is a simulator for drones, cars and more, built on [Unreal Engine](https://www.unrealengine.com/) (with an experimental [Unity](https://unity3d.com/) release). It is open-source, cross platform, and supports hardware-in-loop with popular flight controllers such as PX4 for physically and visually realistic simulations.

- [DroneSimLab](https://github.com/orig74/DroneSimLab): A multi simulation which include multiple simulation engines.
- [Carla](https://github.com/carla-simulator/carla): An open-source simulator for autonomous driving research. 

- [ros-sharp](https://github.com/siemens/ros-sharp): A set of open source software libraries and tools in C# for communicating with ROS from .NET applications, in particular Unity.



## Robotic Operating System (ROS)

Here are the various packages that might suit your needs.

- [ROS 2 Multirobot Book](https://github.com/osrf/ros2multirobotbook): A book on ROS 2 and the RMF system for integrating multiple robots.

### Navigation/SLAM

- [teb_local_planner](http://wiki.ros.org/action/fullsearch/teb_local_planner?action=fullsearch&context=180&value=linkto%3A"teb_local_planner"): A 2D navigation stack base_local_planner plugin that implements Timed Elastic Band.
- [Octomap](https://github.com/OctoMap/octomap): An Efficient Probabilistic 3D Mapping Framework Based on Octrees.
- [Cartographer ROS](https://github.com/cartographer-project/cartographer_ros): [Cartographer](https://github.com/cartographer-project/cartographer) is a system that provides real-time simultaneous localization and mapping ([SLAM](https://en.wikipedia.org/wiki/Simultaneous_localization_and_mapping)) in 2D and 3D across multiple platforms and sensor configurations. This project provides Cartographer's ROS integration.

- [ORB_SLAM2](https://github.com/appliedAI-Initiative/orb_slam_2_ros): A real-time SLAM library for **Monocular**, **Stereo** and **RGB-D** cameras that computes the camera trajectory and a sparse 3D reconstruction (in the stereo and RGB-D case with true scale).

- [ORB_SLAM2_CUDA](https://github.com/thien94/ORB_SLAM2_CUDA): ORB_SLAM2 with CUDA.

- [OpenVSLAM](https://github.com/xdspacelab/openvslam): A monocular, stereo, and RGBD visual SLAM system.

### Pointclouds

- [linefit_ground_segmentation](https://github.com/lorenwel/linefit_ground_segmentation): Ground segmentation of 3D point clouds, paper could be found [here](https://ieeexplore.ieee.org/document/5548059).



## Nvidia Jetson

Various packages related to the Nvidia jetson development boards (e.g. Jeston TX2, Jetson Nano, Jetson NX Xavier).

- [JetsonGPIO(C++)](https://github.com/pjueon/JetsonGPIO): A C++ library that enables the use of Jetson's GPIOs, unofficial port of the NVIDIA's official Jetson GPIO Python library to C++.
- [jetson_stats](https://github.com/rbonghi/jetson_stats): A package to **monitoring** and **control** your [NVIDIA Jetson](http://www.nvidia.com/object/embedded-systems-dev-kits-modules.html) [Xavier NX, Nano, AGX Xavier, TX1, TX2], works with all NVIDIA Jetson ecosystem.
- [Jetson TX1/2 YOLO Darknet](https://github.com/Alro10/YOLO-darknet-on-Jetson-TX2): YOLO-darknet on Jetson TX1/2.