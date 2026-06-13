# Interactive Virtual Tour Web Application

## Overview

This project is an interactive web-based virtual tour application that allows users to explore premises remotely using 360° panoramic images. The application provides smooth navigation between scenes via interactive hotspot elements, an adaptive interface for different devices, and optimized image loading through a containerized server infrastructure.

## Features

- **360° Panoramic Viewing** – Full spherical panorama rendering using WebGL technology
- **Interactive Navigation** – Move between scenes by clicking on hotspot elements
- **Adaptive Interface** – Automatically adjusts to mobile and desktop devices
- **Session State Preservation** – Remembers the last visited scene using localStorage
- **Compass Integration** – Helps users orient themselves within the virtual environment
- **Fullscreen Mode** – Immersive fullscreen viewing experience
- **Zoom Controls** – Smooth zoom in/out functionality

## Tech Stack

### Frontend
- HTML5, CSS3, JavaScript (ES6+)
- [Pannellum.js](https://pannellum.org/) – WebGL-based panorama viewer library

### Backend Infrastructure
- **Nginx** – Web server serving static files
- **MinIO** – S3-compatible object storage for panoramic images
- **Docker** – Containerization platform

### DevOps & Tools
- **GitHub Actions** – CI/CD pipeline for automated deployment
- **Git** – Version control system
- **Visual Studio Code** – Development environment
 
