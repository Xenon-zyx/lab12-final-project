# Lab12 Final Project - Personal Website & Todo App Deployment
## Basic Personal Information
- Full Name: Zou Yaxian
- Nickname: Jade
- Student ID: 20242181
- Personal Photo:
<img src="website/photo.jpg" width="500" alt="My Photo">

## Project Introduction
This is the final assignment of Lab 12. We use Docker, Docker Compose and GitHub Actions to implement integrated automatic deployment for a personal introduction website and an open-source Todo application. Both applications are deployed on the same server.

## Application Access URL
1. Personal Introduction Website: http://13.216.217.67
2. Open-source Todo Application: http://13.216.217.67:3000

## Technology Stack
- Personal Website: HTML, CSS, JavaScript
- Containerization: Docker, Docker Compose
- CI/CD & Automation Deployment: GitHub Actions (Workflow)
- Third-party Application: TodoMVC, source: https://github.com/tastejs/todomvc.git

## Project File Description
1. `Dockerfile`: Configuration file for building the image of personal website
2. `.github/workflows/`: GitHub CI/CD automatic deployment workflow files
3. `docker-compose.yml`: Orchestrate and run both personal website and Todo application services
4. Website source directory: Store all source code of the personal introduction website
