# techdome-task

DevOps Assignment: Multi-Container Application Deployment with Docker Compose and Kubernetes
**Objective**

To deploy a multi-container application using Docker Compose and Kubernetes, ensuring the backend, frontend, and database services are properly configured and functional.
Steps Involved:

**Environment Setup**
Installed Docker, Docker Compose, Minikube, and kubectl to manage containerized applications and Kubernetes clusters.

**Cloning Repositories**
Cloned the backend and frontend repositories from GitHub to obtain the necessary code for the services.

**Creating Dockerfiles**
Created Dockerfiles for both the backend and frontend applications to define how they will be built and run in containers.

**Docker Compose Configuration**
Created a docker-compose.yml file to define and manage the multi-container Docker application locally, including configurations for the backend, frontend, and database services.
Tested the setup using Docker Compose to ensure all services started correctly and could communicate with each other.

**Setting Up Minikube**
Started a local Kubernetes cluster using Minikube to simulate a production-like environment for deploying and testing the application.

**Creating Kubernetes Manifests**
Created Kubernetes deployment and service manifests for the backend, frontend, and database. These manifests define how each service should be deployed, including the number of replicas and exposed ports.
Applied these manifests using kubectl to deploy the services to the Minikube cluster.

**Exposing and Accessing Services**
Used the minikube service command to expose and access the frontend service, ensuring it was correctly mapped and accessible from the host machine.

**Testing and Verification**
Verified that the frontend service was accessible externally and that the backend and database services were functional and reachable.

**Conclusion**
By following these steps, we successfully deployed a multi-container application using Docker Compose and Kubernetes. This involved containerizing the applications, managing services with Docker Compose, and deploying to a Kubernetes cluster using Minikube, ensuring a smooth and efficient deployment process with industry-standard tools and practices.

