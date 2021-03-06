## About
This package uses your idle web-cam as a video recording device. Video recording is triggered based on motion and is data/time stamped. The intention is to develop a smart camera software that can be monitored remotely. I had made a simple UI using QT, the source code is made available so that you can modify and test on your own. If you run into any issues, feel free to contact me. Cheers!

## Screenshots

Screenshot 1                |  Screenshot 2              |    Screenshot 3 
:-------------------------:|:-------------------------:|:-------------------------:
![](https://haixun00.github.io/img/project/motion_cam/pic1.jpg)  |  ![](https://haixun00.github.io/img/project/motion_cam/pic2.jpg) | ![](https://haixun00.github.io/img/project/motion_cam/pic3.jpg)

Screenshot 4                |  Screenshot 5              |    Screenshot 6
:-------------------------:|:-------------------------:|:-------------------------:
![](https://haixun00.github.io/img/project/motion_cam/pic4.jpg)  |  ![](https://haixun00.github.io/img/project/motion_cam/pic5.jpg) | ![](https://haixun00.github.io/img/project/motion_cam/pic6.jpg)

## System Requirements:
- Windows 8/10 (tested on)
- QT 5.3
- Opencv 3.1
- cmake 2.4.3 above

## Additional Info:
Installer is included and please refer to the QT documentation if you want to repackage it for distribution in the future. The technique used is background subtraction, followed by Baye's classifier to filter out the noise and to give a confidence value to determine if there is a presence of motion. There is a short video demo below to show how it works. The collected video is a series of short span in which motion were detected. The blur is intentional for privacy sake.  

## Video Demo:
[![Video Demo](https://img.youtube.com/vi/93rKZjsv5dc/0.jpg)](https://www.youtube.com/watch?v=93rKZjsv5dc)

