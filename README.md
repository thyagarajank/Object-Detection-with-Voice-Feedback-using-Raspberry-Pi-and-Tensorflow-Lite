# Object-Detection-with-Voice-Feedback-using-Raspberry-Pi-and-Tensorflow-Lite

## Introduction
In this Project, I teach you how to set up the TensorFlow Lite and Voice Feedback on the Raspberry Pi and use it to run object detection models with voice feedback. In this work, I will use the Raspberry Pi 3 or Raspberry Pi 4 running either Raspbian Buster or Raspbian Stretch.(Raspbian OS Repo Link: https://downloads.raspberrypi.org/raspbian/images/)
try Raspbian images(2018-2020), They are the supported OS images.

## Lesson 1 - How to Set Up TensorFlow Lite on the Raspberry Pi

### Step 1. Check Python Version in Raspberry Pi
In this tutorial Tensorflow Lite installation currently supported python version is 3.5, 3.6, 3.7 & 3.8 ..
```
python3 --version
```
### Step 2. Update the Raspberry Pi

```
sudo apt update && sudo apt install rpi-update
```
### Step 3. Download My Github Repository

Next step, clone My GitHub repository

```
git clone https://github.com/thyagarajank/Object-Detection-with-Voice-Feedback-using-Raspberry-Pi-and-Tensorflow-Lite.git
```

Unzip the Folder "Object-Detection-with-Voice-Feedback-using-Raspberry-Pi-and-Tensorflow-Lite". Copy the all files to "tflite1" folder.

```
uzip Object-Detection-with-Voice-Feedback-using-Raspberry-Pi-and-Tensorflow-Lite
```

```
mkdir tflite1
```

```
cp -rvf Object-Detection-with-Voice-Feedback-using-Raspberry-Pi-and-Tensorflow-Lite tflite1
```

```
cd /home/pi/tflite1

```
