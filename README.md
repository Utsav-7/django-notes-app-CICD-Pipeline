# Simple Notes App
This is a simple notes app built with React and Django.

## Requirements
1. Python 3.9
2. Node.js
3. React

## Installation
1. Clone the repository
```
git clone https://github.com/LondheShubham153/django-notes-app.git
```

2. Build the app
```
docker build -t notes-app .
```

3. Run the app
```
docker run -d -p 8000:8000 notes-app:latest
```

## Nginx

Install Nginx reverse proxy to make this application available

`sudo apt-get update`
`sudo apt install nginx`

## CI/CD Pipeline

- Below is an image of the CI/CD pipeline used for this application:
![Django-App-CICD](https://github.com/user-attachments/assets/cd76f23d-6fdf-433d-9a14-e80ec0e7511e)

### Description

- This pipeline ensures robust and secure deployment practices by integrating the following tools:

  - **GitHub:** Version control system for managing the source code.
  - **Jenkins:** Automation server to orchestrate the CI/CD pipeline.
  - **OWASP:** Security checks to identify vulnerabilities in the application.
  - **SonarQube:** Static code analysis to ensure code quality and security.
  - **Trivy:** Vulnerability scanner for container images.
  - **Docker:** Containerization for consistent application deployment.
  - **Kubernetes:** Orchestration platform for deploying, scaling, and managing containers.
  - **Grafana/Prometheus:** Monitoring and visualization tools for application performance and health.

This pipeline ensures efficient development workflows and secure, reliable application deployments.

### References

- For more such projects and detailed explanations, visit the [Train With Shubham](https://youtube.com/@trainwithshubham?si=Eh2vw54bqxvEK5oW).
