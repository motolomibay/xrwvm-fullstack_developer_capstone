# Best Cars Dealership

A full-stack web application for **Best Cars Dealership** — a national car retailer with branches across the United States. This platform provides a central database of dealership reviews, enabling customers to browse dealerships, read reviews, and share their own experiences.

## Project Overview

This application was developed as part of the IBM Full-Stack Software Developer Professional Certificate Capstone Project.

## Technologies Used

- **Frontend:** React, HTML5, CSS3, Bootstrap
- **Backend:** Python, Django, SQLite
- **Microservices:** Node.js, Express.js, MongoDB
- **Sentiment Analysis:** Python, Flask, NLTK
- **DevOps:** Docker, Kubernetes, IBM Cloud Code Engine
- **CI/CD:** GitHub Actions
- **Version Control:** Git, GitHub

## Features

- Browse car dealerships across the United States
- Filter dealerships by state
- View dealer reviews with sentiment analysis (positive, neutral, negative)
- User registration and authentication
- Submit reviews for dealerships (authenticated users)
- Admin panel for managing car makes and models
- Responsive design for all devices

## Architecture

The application follows a microservices architecture:

1. **Django Application** - Main web app handling user management and serving the React frontend
2. **Node.js/Express API** - Backend service managing dealer and review data with MongoDB
3. **Flask Sentiment Analyzer** - Microservice for analyzing review sentiments using NLTK
4. **React Frontend** - Dynamic UI components for dealers, reviews, and user interactions

## Author

Developed as part of the IBM Full-Stack Software Developer Professional Certificate.
