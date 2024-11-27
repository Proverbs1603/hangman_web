# CI/CD Workflow with GitHub Actions, Docker, and Production Deployment
![docker_CI_ID (1)](https://github.com/user-attachments/assets/4b1c659a-5120-4e13-acf4-ba92d250e2a9)


This repository demonstrates a complete **CI/CD pipeline** using the following workflow:
1. **Code Push to GitHub**: Developers push code to the repository.
2. **GitHub Actions**: Triggers automated workflows upon code updates.
3. **Docker Image Build**: Builds Docker images and pushes them to Docker Hub.
4. **Production Deployment**: Deploys the latest Docker image to the production server.

## Getting Started

### Prerequisites
- A GitHub repository.
- Docker installed on the local machine.
- A Docker Hub account for storing images.
- SSH access to the production server for deployment.
