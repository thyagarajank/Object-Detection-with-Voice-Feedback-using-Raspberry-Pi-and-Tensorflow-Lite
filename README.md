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
### Step 3. Download & Unzip My Github Repository

clone My GitHub repository

```
git clone https://github.com/thyagarajank/Object-Detection-with-Voice-Feedback-using-Raspberry-Pi-and-Tensorflow-Lite.git
```

Unzip the Folder "Object-Detection-with-Voice-Feedback-using-Raspberry-Pi-and-Tensorflow-Lite". Move the all files to "tflite1" folder.

```
uzip Object-Detection-with-Voice-Feedback-using-Raspberry-Pi-and-Tensorflow-Lite
```
### Step 4 Create New Directory
Create New Dir at (/home/pi/)
```
mkdir tflite1
```
Move all Files to "tflite1"
```
mv Object-Detection-with-Voice-Feedback-using-Raspberry-Pi-and-Tensorflow-Lite tflite1
```
Work in this "/home/pi/tflite1" directory.
```
cd /home/pi/tflite1
pwd
```
### Step 5 Create a Virtual Environment called "tflite1-env".
Intall Virtualenv
```
sudo pip3 install virtualenv
```
Create the "tflite-env" Virtual Environment
```
python3 -m venv tflite1-env
```
Activate Virtual Environment
```
source tflite1-env/bin/activate
```
### Step 6 Install TensorFlow & Other Dependencies.
OpenCV  required packages and other libraries mention in .sh (shell) script. it will automatically download and installed.
```
bash install_tflite_requirements.sh
```
Install Tensorflow
```
pip3 install tensorflow==1.14
```
### Step 7 Download Google's sample TFLite model
SSDLite-MobileNet-v2 object detection model run on TensorFlow Lite
```
wget http://download.tensorflow.org/models/object_detection/ssdlite_mobilenet_v2_coco_2018_05_09.tar.gz
```
