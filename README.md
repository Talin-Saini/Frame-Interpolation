#  Image-to-Video Frame Interpolation Web App (Google FILM)

This repository contains a web-based frame interpolation application that generates a smooth video sequence from two input images using Google’s FILM (Frame Interpolation for Large Motion) model. The application is built using Gradio, providing an interactive interface for image-to-video generation. A demo video demonstrating the working of the application is also included in this repository.

---

##  Project Overview

Frame interpolation synthesizes intermediate frames between two given images to create smooth motion. In this project, users upload two images (start and end frames), a deep learning–based FILM model predicts intermediate frames, the generated frames are compiled into a video output, and the entire pipeline is accessible through a Gradio web interface.

---

##  Features

- High-quality frame interpolation using Google FILM  
- Interactive Gradio web app  
- Image-to-video generation from two still images  
- Smooth temporal transitions  
- Configurable interpolation parameters  
- Demo video included  

---

##  Model Used

FILM (Frame Interpolation for Large Motion) is a neural network designed to handle large object motion, maintain temporal consistency, and reduce motion blur and interpolation artifacts. It outperforms traditional optical-flow–based interpolation methods, especially for scenes with large motion.

---

##  Pipeline

Input Image 1  
→ FILM Model  
→ Intermediate Frames  
→ Video Output  
← Input Image 2

---

##  Tech Stack

- Python  
- Google FILM  
- Gradio  
- NumPy  
- OpenCV / ImageIO  

---


##  Demo

This is the video demonstrating how the website works


https://github.com/user-attachments/assets/af9e70ed-f503-4d34-b118-0a11932e5d68


---

## Use Cases

- Video frame interpolation and upsampling  
- Image-to-video synthesis  
- Animation and visual effects  
- Research and academic demonstrations  
- Educational visualization of temporal modeling  

---

