# Argo CD GitOps Deployment on Kubernetes using Kind

## Project Overview

This project demonstrates GitOps-based application deployment on Kubernetes using Argo CD.

I created a Kubernetes cluster using Kind, installed Argo CD, connected my GitHub repository, and deployed an application through the Argo CD Web UI.

## Technologies Used

- Kubernetes
- Kind (Kubernetes in Docker)
- Argo CD
- Docker
- Docker Hub
- GitHub

## Implementation Steps

1. Created a Kubernetes cluster using Kind.
2. Installed Argo CD in the Kubernetes cluster.
3. Accessed the Argo CD dashboard using port forwarding.
4. Connected the GitHub repository to Argo CD.
5. Created an Argo CD application using the Web UI.
6. Deployed an application using the Nginx Docker image.
7. Updated the deployment to use a custom Docker Hub image.
8. Configured Kubernetes Services and port forwarding to access the application.
9. Troubleshot connectivity issues by inspecting Pods, Services, and application logs.

## Key Learnings

- Understanding GitOps principles.
- Argo CD application configuration.
- GitHub integration with Argo CD.
- Kubernetes Deployments and Services.
- Container image deployment.
- Troubleshooting Kubernetes applications.

## Project Status

Initial deployment completed successfully. Further GitOps experiments and improvements are planned.

## Author

Vaishnavi Bhoite
