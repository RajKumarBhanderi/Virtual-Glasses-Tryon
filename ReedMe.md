# 👓 Virtual Glasses Try-On (Web-Based AR Application)

This project is a **real-time browser-based Virtual Try-On system for eyeglasses**, using **JavaScript**, **MediaPipe**, **Three.js**, and **TensorFlow.js**. It detects facial landmarks and overlays 3D eyeglasses using your device camera, without requiring any downloads or installations. All processing is done in the browser to ensure speed, performance, and privacy.

---

## 🚀 Features

- Real-time face tracking using **MediaPipe FaceMesh**
- Accurate placement of 3D eyeglasses using facial landmarks
- Lightweight deployment (no backend required)
- Eyeglass switching and customization (color, size, transparency)
- Fully browser-based: no installation or facial data storage
- Built-in accessibility and responsive UI design

---

## 🛠️ Installation & Setup

### 🔧 Requirements

- Node.js installed on your system [Download here](https://nodejs.org/)
- A modern browser (Chrome or Firefox recommended)
- VS Code or any code editor for editing
- Internet connection (for loading some libraries via CDN)

---

## Use any of the following options:

# Option A – With http-server (Recommended)

npm install -g http-server
http-server .

# Option B – With VS Code "Live Server" Extension
Open folder in VS Code

Right-click index.html > "Open with Live Server"

Once the server is running, go to:

http://localhost:8080


## Face Keypoints 
The facemesh detected keypoints that used for overlay the 3D Glasses:
* Middle between Eyes : 168
* Left Eye : 143
* Bottom of Nose : 2
* Right Eye : 372

## Try glasses on
* Click "Try it On" to turn on the Webcam switch, and allowing the browser to access your webcam 
* Wait for a few seconds to Load Model for face landmark detection
* Choose the 3d glasses you would like to try on, watch yourself in fashion


## Library
* [three.js](https://threejs.org/) - JavaScript 3D Library
* [facemesh](https://ai.google.dev/edge/mediapipe/solutions/vision/face_landmarker)- MediaPipe Facemesh is a lightweight machine learning pipeline predicting Face landmark

## Credit 3D glasses models
* [Sport Glasses B307](https://sketchfab.com/3d-models/sport-glasses-b307-7630c4ac090c42598de43d47554b4cf4) by	hanchiahui
* [Glasses 07](https://sketchfab.com/3d-models/glasses-07-06b22104f56a4356aa9ffa825abd8d6b) by	Dokono Kinokoda
* [Cartoon Glasses](https://sketchfab.com/3d-models/cartoon-glasses-fddd63a49615405fb17f5c7ff65345c2) by	Lucas_Bartolomeo
* [Plastic Sunglasses](https://sketchfab.com/3d-models/plastic-sunglasses-d5417dcb97fb41b39f57fc8772a7ecab) by	Incg5764
* [Aviator sunglasses](https://sketchfab.com/3d-models/aviator-sunglasses-00d1cb5aa82745228a3b764c97f867de) by	Kimppo