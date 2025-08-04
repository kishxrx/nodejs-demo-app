# Node.js CI/CD Demo App 🚀

This is a sample Node.js application with a fully automated **CI/CD pipeline** using **GitHub Actions** and **DockerHub**.

##  Overview

This project demonstrates how to:
- Build and test a Node.js application
- Automatically build a Docker image
- Push the Docker image to DockerHub
- Trigger the entire workflow on every push to the `main` branch

## 🔧 Tech Stack

- Node.js
- GitHub Actions
- Docker & DockerHub

##  CI/CD Workflow Summary

The GitHub Actions workflow does the following:

1. 📥 Checkout the repository  
2. ⚙️ Set up Node.js environment  
3. 📦 Install project dependencies  
4. ✅ Run unit tests (`npm test`)  
5. 🏗️ Build the Node.js app  
6. 🐳 Build Docker image  
7. 🔐 Login to DockerHub using GitHub Secrets  
8. 🚀 Push image to DockerHub repository  

##  Docker Image

You can find the built Docker image here:

👉 **[DockerHub Repo Link](https://hub.docker.com/r/kishxrx/nodejs-demo-app)**  
*(Replace with your actual DockerHub link)*

## 📂 File Structure
