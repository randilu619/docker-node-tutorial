Node.js Application Containerization & Docker Hub Registry Workflow
Project Description
Developed a RESTful API using Node.js and Express, integrated with external data fetching, and implemented a complete containerization pipeline. The project focused on transitioning from a local development environment in VS Code to a production-ready container image hosted on Docker Hub.

Key Features
RESTful API Development: Built a Node.js backend using Express to handle asynchronous data fetching from external endpoints.

Environment Configuration: Managed project dependencies and environment variables using .env and package.json for consistent application behavior.

Docker Image Tagging & Versioning: Utilized Docker CLI to tag images with specific versions (e.g., v1) for better release management.

Automated Registry Push: Successfully pushed the specialized Node.js image to a public Docker Hub repository (randiluprathibha/node-newv1) for remote deployment.

Technical Workflow & Screenshots
1. VS Code & Node.js Development
Developing a scalable Node.js backend in VS Code, featuring asynchronous middleware and clean environment separation.

Caption: Writing the server logic and managing the environment in VS Code.

2. Pushing to Docker Hub
Successfully pushing the node-newv1:v1 image to Docker Hub, ensuring the application is ready for seamless deployment anywhere.

Caption: Using the Docker CLI to tag and push the image to the registry.

3. Pulling the Image
Verifying portability: Pulling the containerized Node.js app from the registry to a clean environment to ensure "it works on every machine".

Caption: Testing the image by pulling it back from the cloud.

How to Run Locally
Clone the repository:
git clone https://github.com/randilu619/docker-node-tutorial.git

Build the Docker Image:
docker build -t node-newv1 .

Run the Container:
docker run -p 5000:5000 node-newv1
