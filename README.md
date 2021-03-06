# Overview of Application

**Version 1.0.0**

OpenVINO Application for implementing AI at the Edge

Deployable on Raspberry Pi Linux, Windows 10.

Please use this as reference on the basics of OpenVINO:

https://docs.openvinotoolkit.org/latest/index.html

## How to Use the Application

Please make sure to have all prerequisites installed:

1. Proper download to OpenVINO on the appropriate version(Version 2021.4)
2. numpy 1.18.5
3. OpenCV 2.4.2
4. Python 3.6 - 3.8

Note: If using a Raspberry Pi, please make sure to have injected a VPU into one of the USB slots.

Commands Possible to Use:

[-v]: Video: file path for video to be interpreted. Within the "Samples" folder, there are sample videos provided. Default is camera feed. 

[-d]: Device: For which device to run the sample on (Ex: CPU, VPU, etc.). Please refer to available devices through here: https://docs.openvinotoolkit.org/latest/openvino_docs_IE_DG_supported_plugins_Supported_Devices.html
-h: Help: to list commands available.

Example command line run of the program: python app.py -v "[path-to-folder]\Project_LPD\Main\Samples\Test1.mp4" -d CPU

Note: If using camera feed 

### License & Copyright
By: Brennan Freeze
All rights go to Intel and their copyright agreements for using the OpenVINO toolkit.
