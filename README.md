# Robotics Onboarding Resources 


## Linux 

- https://www.trybash.com
- https://try.github.io
- https://www.codecademy.com/learn/learn-git
- https://www.codecademy.com/learn/learn-the-command-line

Ubuntu 18.04 is the recommend flavour which will be used to build/complie
projects.

#### WSL 2 (Windows Only)
Some software that we run requries a Linux kernel. Running 
this sofware can be done on VirtualBox or WSL2(Windows only) 
if you are not comfertable dual booting Linux on your 
computer. 

- https://www.windowscentral.com/how-install-wsl2-windows-10

### Docker

- https://docs.docker.com/get-started/
- https://docs.docker.com/reference/

## GIT
Git is a version control software that is very commonly used
in industry.

## General purpose programming languages

Python is a easy language to us for protyping. C/C++ should be used only when
required to write drivers or tasks that require effective computations.

### Python
- https://www.codecademy.com/learn/learn-python
- https://www.youtube.com/watch?v=anrOzOapJ2E

### C/C++
- http://www.engineer4free.com/cplusplus.html


## Database

### SQL
- https://www.codeschool.com/courses/try-sql
- https://www.codecademy.com/learn/learn-sql


## Embedded

### Arduino
Arduino uses the C++ programming language and builds on top of it with its own
libraries. Make sure to familiarize yourself with C++ to a basic level before 
starting with Arduino.

- http://forefront.io/a/beginners-guide-to-arduino/

### STM32
For the microprocessors on the boards we use STM32 Chips. These have 
better preformance than the arduino boards and give us more flexiblity in 
which lanuage we want to use. We develop these boards in C, but some parts
have been programed in C++. 

- https://uoguelphca.sharepoint.com/:f:/r/sites/UGRT2/Rover/Electrical/Embedded/STM32%20Details?csf=1&web=1&e=1vqah5

## ROS(1)
ROS (Robot Operating System) isn't really an operating system, but rather a 
framework for building and communicating with Robots. The core is written is
C++, but many modules are also available in Python 2.

Also note, ROS Melodic is currently only supported on Ubuntu 18.04 (last checked: 2021-11-14).

- http://wiki.ros.org/ROS/Tutorials

## ROS 2
ROS2 is the sucessor to ROS(1) which has a better design for both deterministic systems and consistancy.
The main Python version is Python 3. 

We are going to be using ROS humble, which is supported on Ubuntu 22.04.
There is also support on Windows, but our end product will be running on Ubuntu.

### Install
- https://docs.ros.org/en/humble/Installation.html
### Tutorials
- https://docs.ros.org/en/humble/Tutorials.html

# Recommended Navigation Software Onboarding Path

- Python
  - https://cscircles.cemc.uwaterloo.ca/
  - https://www.codecademy.com/learn/learn-python (requires account)
  - https://www.theconstructsim.com/robotigniteacademy_learnros/ros-courses-library/python-robotics/ (requires account: leads well into ROS)
- Linux and Bash
  - https://www.theconstructsim.com/robotigniteacademy_learnros/ros-courses-library/linux-for-robotics/ (requires account: leads well into ROS)
- ROS 2 Tutorial
  - https://docs.ros.org/en/humble/Tutorials.html
- Docker & Docker Compose
  - https://serversforhackers.com/s/docker-in-dev-v2-i
  - https://serversforhackers.com/s/docker-in-dev-v2-ii
