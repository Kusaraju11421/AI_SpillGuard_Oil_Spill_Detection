🛢️ AI-Driven Oil Spill Detection System








📌 Overview

An AI-powered system that detects and segments oil spills from satellite imagery using deep learning. The solution automates oil spill identification, enabling faster response and reduced environmental damage.

🌊 Problem

Manual oil spill detection methods are slow, labor-intensive, and delayed, increasing risks to marine ecosystems and coastal regions.

🧠 Solution

Using CNN / U-Net architectures, the system:

🔍 Detects oil spill regions

🧩 Generates pixel-level segmentation masks

🚨 Supports real-time monitoring and early intervention

🧩 Workflow
Satellite Images
       ↓
Data Preprocessing & EDA
       ↓
Deep Learning Model (CNN / U-Net)
       ↓
Oil Spill Segmentation Mask
       ↓
Visualization & Web App Deployment


📷 Add your workflow or architecture diagram here:
/assets/workflow.png

🎯 Key Features

🛰️ Satellite image-based detection

🤖 Deep learning-driven segmentation

🎯 High-precision oil spill localization

📊 Visual result interpretation

🌐 Web-based interface

🛠️ Tech Stack

Language: Python 🐍

Models: CNN, U-Net

Libraries: NumPy, Pandas, OpenCV

Deployment: Streamlit / Flask

▶️ Run Locally

This contains everything you need to run your app locally.

Prerequisites:

Node.js

Steps

Install dependencies

npm install


Set the GEMINI_API_KEY in .env.local

GEMINI_API_KEY=your_api_key_here


Run the app

npm run dev

🌐 Deployment

🚀 Deployable using Streamlit Cloud / Vercel / Local Server

🌍 Accessible via browser for real-time oil spill monitoring

🔧 Easily scalable for production environments

🌍 Impact

Supports environmental agencies with rapid oil spill detection, helping protect marine life, coastal regions, and ecosystems.
