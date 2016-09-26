#Project: MaterBot

###Description

This project is intended to be the base project from which each season's Java RoboRio controller project is derived from. 

###Purpose

WPILib does provide the base robot framework, however this framework is very basic.  The purpose of this project is to built upon the foundation provided by WPILib and add additional features that can be used from season to season.

Typically, the Robot class is derived from the IterativeRobot class.  MDRobotBase interjects a class in the middle of the hierarchy to add new features and improve other features.

![MDRobotBase Class Hierarchy](https://www.gliffy.com/go/publish/image/11017397/L.png)


###Features
* Improved Configuration
* MDConsole Support
* Improved Logging
* Core Subsystem
* WebSockets Subsystem
* Diagnostics Subsystem
* Drive Sybsystem
* ADIS16448_IMU Gyro Implementation

###Typical Use
Typically, this project would be forked for each season.

See the [How to Git](https://github.com/MDHSRobotics/TeamWiki/wiki/How%20to%20Git) tutorial for more information on how to fork this project.  
