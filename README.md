# docker-node-tutorial
# Node.js API Containerization Project

This project demonstrates a complete DevOps workflow for a Node.js application, from local development to a cloud-ready Docker image.

## Features
- **Express API**: Fetches and serves data asynchronously.
- **Dockerized**: Includes a custom Dockerfile for environment consistency.
- **Registry Integration**: Integrated with Docker Hub for automated image distribution.

## How to Run
1. Clone the repo: `git clone https://github.com/randilu619/docker-node-tutorial.git`
2. Build the image: `docker build -t node-newv1 .`
3. Run the container: `docker run -p 5000:5000 node-newv1`
