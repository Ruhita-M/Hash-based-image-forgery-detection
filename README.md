# 🕵️‍♂️ Image Forgery Detection Web Application 

This image analysis tool is a lightweight web application developed as part of a college project (AY 2023–24). It helps detect tampering or forgery in images by converting them to grayscale and comparing perceptual hash values. The project demonstrates how simple techniques like image hashing can provide quick insights into image authenticity.


## 👥 Team Members

- Ruhita M [Ruhita-M](https://github.com/Ruhita-M)  


## 🚀 Features

- 🖼️ Image Upload Interface – Upload and compare two images via a clean web interface  
- ⚙️ Grayscale Conversion – Standardizes images for uniform analysis  
- 🔍 Perceptual Hashing – Uses image hash comparison to detect forgeries  
- 📉 Tamper Detection Result – Instantly displays whether the image is forged or authentic  
- 🧪 Lightweight Processing – Built for speed and minimal resource usage  
- 🌐 Web-Based – Flask-powered local web server for platform-independent access  


## 🛠️ Tech Stack

 Layer             - Technologies Used                   
---------------------------------------------------
 Frontend (GUI) -   HTML, CSS (via Flask templating)     
 Backend (API) -    Python (Flask)                       
 Image Processing - Pillow, ImageHash                    
 Logic Layer -      Grayscale conversion, Hash comparison
 Hosting (Local) -  Flask development server             


## 📦 System Architecture

The application consists of the following layers:

1. User Interface – HTML-based form interface for selecting and uploading images  
2. Flask Backend – Handles file uploads, and hash comparison logic  
3. Image Processing Module – Uses ImageHash to convert images and compute hashes  
4. Logic Layer – Compares hashes and determines similarity/tampering  
5. Result Display – Outputs clear verdict: “Forged” or “Not Forged”

