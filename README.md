# My Camera Control Package

This is a Python package that provides functionalities to control and manage two endoscope cameras. The package provides a simple API to capture frames from each camera and save the video streams 
to files.

## Installation

You can install the package using pip:

```bash
pip install my_camera_control_package

Usage
Here's a basic example of how to use the package:

from my_package import camera_control

camera_save_1='E:\\video\\endo1.mp4'
camera_save_2='E:\\video\\endo2.mp4'
camera_control.run(camera_save_1,camera_save_2)

In this example, the run function is used to capture video streams from two endoscopes and save the streams to the specified files.

Contributing
Contributions are welcome! Please open an issue if you encounter any problems, or open a pull request if you want to contribute your code.


You can replace `"my_camera_control_package"` and `"my_package"` with the actual name of your package. This README provides a good starting point and you can expand it as your package grows and 
gains more functionalities.

