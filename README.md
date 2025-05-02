Food Delivery Application
This repository contains the full-stack Food Delivery Application, built using Microservices Architecture. The application provides users with an interactive platform for food ordering and restaurant browsing.

Technologies Used:
Frontend: TypeScript, Angular 16

Backend: Java, Spring Boot, Microservices

Database: MySQL (RDS), MongoDB (Atlas, MongoCompass)

CI/CD: Jenkins, SonarQube, ArgoCD

Containerization & Orchestration: Docker, Kubernetes (AWS EKS)

Cloud: AWS (IAM, RDS, EC2, EKS)

Overview
The application is developed using Microservices, where each service is independently deployable and communicates with other services. The services are containerized using Docker and deployed on AWS Kubernetes (EKS) for efficient scaling and orchestration. The application follows a CI/CD pipeline, where Jenkins is used for continuous integration, SonarQube is integrated for code quality analysis, and ArgoCD is used for deployment automation.

Deployment & Configuration
All microservices are deployed using AWS EKS and configured for high availability and fault tolerance. The Eureka service acts as the service registry, enabling seamless communication between microservices.

For deployment configurations, refer to the Deployment Configuration Guide.

Screenshots
Microservice Registered on Eureka

This screenshot shows the registered microservices on Eureka, deployed on AWS Kubernetes.

Jenkins CI Pipeline

This screenshot shows the Jenkins CI pipeline running the build and tests.

SonarQube Code Quality Report

This screenshot shows the code quality report from SonarQube.

ArgoCD Deployment on AWS

This screenshot shows the ArgoCD dashboard with the deployed microservices on AWS EKS.

Getting Started
Prerequisites
Node.js and Angular CLI for the frontend

Java 17+ and Spring Boot for the backend

Docker for containerizing the application

Kubernetes (AWS EKS) for orchestration

Installation
Clone the repository:

bash
Copy
git clone https://github.com/sgovindrana/food-delivery-application
Set up the frontend:

bash
Copy
cd food-delivery-application-fe
npm install
ng serve
Set up the backend microservices by navigating to each service directory and following the individual setup instructions.

Deploy the application on AWS EKS using Kubernetes configurations.
