# Visual Studio Code Robot Developer Extensions for ROS 1

The Robot Developer Extensions (RDE) is a set of extensions for [Visual Studio Code][vscode]. This extension provides support for the Legacy [Robot Operating System (ROS)][ros] 1 runtime, an open-source robotics middleware producted by [Open Robotics](https://www.openrobotics.org/) and supports development on Windows and Linux. 

> NOTE: This extension is rebranded and re-released by Ranch Hand Robotics, owned by the maintainer of the [MS-IOT VSCode ROS Extension](https://github.com/ms-iot/vscode-ros) with permission from Microsoft. 

## Features

* Automatic ROS environment configuration.
* Allows starting, stopping and viewing the ROS core status.
* Automatically create `catkin_make` or `catkin build` build tasks.
* Create catkin packages using `catkin_create_pkg` script or `catkin create pkg`.
* Run `rosrun` and `roslaunch`
* Resolve dependencies with `rosdep` shortcut
* Syntax highlighting for `.msg`, `.urdf` and other ROS files.
* Automatically add the ROS C++ include and Python import paths.
* Format C++ using the ROS `clang-format` style.
* Preview URDF and Xacro files.
* Debug a single ROS node (C++ or Python) by [attaching to the process][debug_support-attach].
* Debug ROS nodes (C++ or Python) [launched from a `.launch` file][debug_support-launch].
