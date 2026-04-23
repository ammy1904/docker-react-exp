# Dockerize React Application with Multi-Stage Build

## Aim
To containerize a React application using Docker multi-stage builds for optimized production deployment.

## Objectives
1. Create Dockerfile with build stage
2. Configure production-ready Nginx server
3. Optimize image size
4. Handle environment variables
5. Build and run Docker container

## About the Program
This project demonstrates containerization of a React application using Docker multi-stage build for efficient production deployment. The React app is first built using Node.js and then served through Nginx.

## Learning Outcomes of Experiment
- Learned how to create a React application
- Understood Docker multi-stage builds
- Learned how to use Nginx for serving production build
- Understood image size optimization
- Learned container-based deployment of frontend applications

## Tools Used
- Docker 20.10+
- Node.js 18+
- React 18+
- VS Code

## Files Included
- Dockerfile
- nginx.conf
- React source code
- README.md

## Build Commands

### Run React locally
```bash
npm install
npm start