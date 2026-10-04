# Node.js CI/CD Demo Application

## Overview

This project demonstrates an automated CI/CD pipeline for a simple Node.js web application using GitHub Actions and Docker.

Whenever code is pushed to the `main` branch, GitHub Actions automatically:

1. Checks out the source code
2. Sets up Node.js
3. Installs dependencies
4. Runs tests
5. Logs in to Docker Hub
6. Builds the Docker image
7. Pushes the Docker image to Docker Hub

## Technologies Used

- Node.js
- GitHub
- GitHub Actions
- Docker
- Docker Hub
- JavaScript

## Project Structure

```text
nodejs-demo-app/
│
├── server.js
├── package.json
├── package-lock.json
├── Dockerfile
├── README.md
│
└── .github/
    └── workflows/
        └── main.yml