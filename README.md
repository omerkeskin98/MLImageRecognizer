# Image Recognition iOS App

## Overview
This iOS app utilizes machine learning to recognize objects in images using the MobileNetV2 model implemented with Core ML. With this app, you can simply take a photo or choose an existing one from your device's library, and the app will identify the objects present in the image.

## Features
- Image recognition using MobileNetV2 model
- Camera integration to capture real-time images
- Option to choose images from the device's photo library
- Real-time inference for quick results

## Installation
### Requirements
- iOS device running iOS 11.0 or later
- Xcode 11.0 or later
- Swift 5.0 or later

### Steps
1. Clone this repository to your local machine.
2. Open the project in Xcode.
3. Build and run the project on your iOS device.

## Usage
1. Open the app on your iOS device.
2. Grant the app permission to access your device's camera and photo library if prompted.
3. To recognize an object in real-time, tap the camera icon to open the camera.
4. Aim the camera at the object you want to identify and wait for the app to recognize it.
5. Alternatively, you can choose an existing photo from your device's library by tapping the gallery icon.
6. After selecting the image, the app will process it and display the identified objects.

## Model
The MobileNetV2 model used in this app is a convolutional neural network architecture designed for efficient on-device image classification. It is capable of recognizing a wide variety of objects with high accuracy while being optimized for mobile and embedded devices.
