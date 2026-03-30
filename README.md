
## Overview
This project demonstrates deployment of a Flask web application on AWS using Docker.

## Architecture
- Amazon EC2 (Compute)
- Docker (Containerization)
- Flask (Backend)
- HTML (Frontend)

## Features
- Containerized Flask application
- Deployed on AWS EC2
- Scalable and portable setup

## Project Structure
- flask/ → Application code
- templates/ → HTML files
- requirements.txt → Dependencies
- Dockerfile → Container setup

## Setup Instructions

1. Clone the repository
2. Build Docker image:
   docker build -t flask-app .

3. Run container:
   docker run -d -p 8080:8080 flask-app

## Learnings
- Learned Docker containerization
- Understood AWS EC2 deployment
- Gained hands-on DevOps experience
