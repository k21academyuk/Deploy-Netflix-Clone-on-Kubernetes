Welcome to the Netflix Infrastructure Modernization Project! This project focuses on streamlining and modernizing Netflix's application deployment infrastructure through the adoption of cutting-edge technologies. Follow the steps below to understand and execute the different phases of the project.

## Project Phases:

### 1. Deploy Netflix Locally on VM (10 points):
- Clone the Netflix clone application from the GitHub repository.
- Build the Netflix image using provided Docker commands.
- Verify the built Docker image.
- Run the Netflix container locally on the VM.
- Check the running container status.
- Access the Netflix application through the browser using the VM's public IP and port.

### 2. Setup Netflix API (12 points):
- Visit TMDB (The Movie Database) to obtain an API key.
- Set up API key access for Netflix.
- Delete existing container and image (if any).
- Build a new Netflix image with the TMDB API key.
- Run the new Netflix container.
- Verify the running container status.
- Access the Netflix clone app with the integrated API.

### 3. Implementation of Security with SonarQube and Trivy (18 points):
- Install SonarQube container on port 9000.
- Access SonarQube in the browser and update credentials.
- Set up Trivy on the system using apt-get commands.
- Verify Trivy installation.
- Use SonarQube for code quality analysis.
- Integrate Trivy to scan Docker images for vulnerabilities.
- Implement security checks in the CI/CD pipeline.

### 4. Setup CI/CD Using Jenkins (21 points):
- Install Java and Jenkins on the server.
- Access Jenkins in the browser using the public IP.
- Retrieve the Jenkins secret key.
- Install necessary Jenkins plugins for Docker, SonarQube, and more.
- Add credentials for SonarQube and Docker in Jenkins.
- Set up Jenkins tools for JDK, Node.js, Docker, SonarQube scanner, and OWASP Dependency-Check.
- Configure global settings for SonarQube in Jenkins.
- Create Jenkins projects for the Netflix application.
- Define Jenkins pipeline stages for build, security checks, and deployment.
- Run the Jenkins pipeline and monitor the build process.

### 5. Running the Pipeline (36 points):
- Execute the Jenkins pipeline for Netflix deployment.
- Ensure the successful execution of Docker image builds.
- Perform security checks using SonarQube and Trivy.
- Deploy the Netflix clone application on the Docker host.
- Verify the new Netflix container and image.
- Check DockerHub for the deployed image.
- Access the running Netflix container through the browser.
- Monitor the pipeline for any errors or issues.

### 6. Deploy Netflix Clone on Kubernetes (39 points):
- Clone the repository for Kubernetes configurations.
- Edit deployment.yml to include the Netflix image and apply changes.
- Create deployment and service configurations for Kubernetes.
- Apply the configurations to deploy the Netflix clone on the Kubernetes cluster.
- Verify the pods and service status in Kubernetes.
- Access the deployed application using the public IP and NodePort.
- Ensure successful deployment on the Kubernetes cluster.
- Clean up resources and turn off VMs for optimization.
