Simple-Docker-DevOps

Project Overview

This project demonstrates a simple Node.js application containerized using Docker, showcasing fundamental DevOps practices. The application is a basic Express server that responds with "Hello, Docker!" when accessed.

Features

- Docker Integration: The application is containerized using Docker, ensuring consistent environments across development, testing, and production.
- DevOps Practices: Incorporates continuous integration and deployment workflows.
- Scalable Architecture: Easily scalable using container orchestration platforms.

How to Run

1. Build the Docker Image:
   docker build -t simple-docker-app .

2. Run the Docker Container:
   docker run -p 3000:3000 simple-docker-app

Visit http://localhost:3000 to see the application in action.

