# Spring-Boot-App-to-Kubernetes-using-Minikube

In this project, I’ll walk you through how I containerized a simple Spring Boot application and deployed it to a **Kubernetes cluster** locally using **Minikube**. This hands-on project helped me understand how real-world microservices are deployed using Kubernetes and gave me practical exposure to core DevOps tools like Docker, Kubernetes, and Spring Boot.

## 🧱 Tech Stack

- Java Spring Boot
- Docker
- Kubernetes + Minikube
- Maven
  
## 🎯 Use Case

This project helps simulate a real-world microservice deployment pipeline:
- Containerizing a Spring Boot application
- Deploying it into a Kubernetes cluster
- Accessing the application locally using Minikube

## 🛠️ Setup Instructions

**⚙️ How This Project Was Built**

✅ 1. Create a Spring Boot Application
A basic REST API was created using Spring Boot with a simple Hello, Kubernetes! endpoint.
✅ 2. Containerize the App with Docker
The Dockerfile builds a Docker image from the Spring Boot app.
✅ 3. Set Up Minikube & Kubernetes:
Use Minikube’s Docker daemon to make images available inside the cluster
✅ 4. Create Kubernetes Deployment & Service
deployment.yaml creates Pods from the Docker image.
service.yaml exposes the app via a ClusterIP service.


## 🧱 Architecture Diagram

![image](https://github.com/user-attachments/assets/8c32dd88-2269-4784-ae6c-f8d75dda4f8d)



