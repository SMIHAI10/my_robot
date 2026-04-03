## Robot Package Template

This is a GitHub template. You can make your own copy.
The code is tested in Gz Harmonic and Rviz with Ros2 Jazzy. The robot navigates in simulation and in real world.

Hardware: 
RPI4 with 4GB
Arduino Nano
L298N
5V Buck Converter
3S Li-Ion battery
2xDC motors with encoders
Lidar - Slamtec A3M1
Camera - RPI Camera Module V2

It is recommended that you keep the repo/package name the same, but if you do change it, ensure you do a "Find all" using your IDE (or the built-in GitHub IDE by hitting the `.` key) and rename all instances of `my_bot` to whatever your project's name is.

Note that each directory currently has at least one file in it to ensure that git tracks the files (and, consequently, that a fresh clone has directories present for CMake to find). These example files can be removed if required (and the directories can be removed if `CMakeLists.txt` is adjusted accordingly).
