# Flask CI/CD Pipeline with GitHub Actions and Docker

## Project Overview
A CI/CD pipeline that automatically builds and deploys 
a Dockerized Python Flask application to Docker Hub 
on every code commit using GitHub Actions.

## Tools & Technologies
- Python (Flask)
- Docker
- GitHub Actions
- Docker Hub

## How It Works
1. Developer pushes code to the main branch on GitHub
2. GitHub Actions automatically triggers the CI/CD pipeline
3. Pipeline builds a Docker image of the Flask application
4. Docker image is pushed to Docker Hub automatically

## CI/CD Pipeline Stages
- Checkout code
- Set up Python
- Install dependencies (Flask, Pytest)
- Run automated unit tests
- Login to Docker Hub
- Build Docker image
- Push image to Docker Hub

## Docker Hub Image
https://hub.docker.com/r/nazeer216/flask-cicd-app

## Project Structure
- app.py — Flask application
- Dockerfile — Container configuration
- .github/workflows/docker-deploy.yml — CI/CD pipeline


