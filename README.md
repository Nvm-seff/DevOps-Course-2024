# DevOps Course 2024: My Learning Journey

Welcome to my GitHub repository for the DevOps Course 2024! This repository is a comprehensive guide to my learning and contributions in the field of DevOps. Below, you will find a summary of my two key blogs, a sample repository from the internet showcasing DevOps practices, and an application of various DevOps tools and techniques. I've also included insights into my knowledge expansion throughout the course.

## Blogs Summary

### 1. [Setting Up Hyperledger Fabric and Hyperledger Explorer Using Docker and Docker Compose](https://medium.com/@saifullah.rizv/setting-up-hyperledger-fabric-and-hyperledger-explorer-using-docker-and-docker-compose-ef0f079ab688)
In this blog, I walk you through the entire process of setting up a blockchain network using **Hyperledger Fabric**, which is a permissioned blockchain platform designed for enterprise solutions, and **Hyperledger Explorer**, a web-based tool for viewing and interacting with the blockchain network. I leverage **Docker** and **Docker Compose** to streamline the deployment and configuration process, allowing for rapid setup and easy scalability. 

By following this guide, you’ll be able to:
- Deploy Hyperledger Fabric using Docker containers.
- Set up a local instance of Hyperledger Explorer for blockchain data visualization.
- Understand the basic principles of permissioned blockchain networks and how to interact with them.

#### Key Learnings:
- Practical steps for deploying Hyperledger Fabric and Explorer in a Dockerized environment.
- How to interact with blockchain networks using Explorer.
- The significance of Docker Compose for simplifying multi-container applications.

### 2. [Infrastructure as Code (IaC): The Backbone of Modern DevOps](https://medium.com/@saifullah.rizv/infrastructure-as-code-iac-the-backbone-of-modern-devops-0bed7d019608)
In this blog post, I explore **Infrastructure as Code (IaC)**, which is a key component in modern DevOps practices. IaC allows teams to automate the provisioning and management of infrastructure using machine-readable configuration files, which in turn promotes consistency, reduces human error, and speeds up deployment cycles. I delve into the most popular IaC tools, including **Terraform** and **Ansible**, and discuss their integration into DevOps workflows to enable automated infrastructure management and deployment.

By reading this blog, you’ll gain insights into:
- The core principles of IaC and its impact on DevOps practices.
- How to use IaC tools like Terraform and Ansible to automate infrastructure provisioning.
- The benefits of IaC in improving system reliability, scaling infrastructure, and achieving faster development cycles.

#### Key Learnings:
- The importance of IaC in modern DevOps pipelines.
- How IaC tools like Terraform and Ansible help in automating infrastructure deployment.
- Understanding the link between IaC and continuous integration/continuous deployment (CI/CD) pipelines.
## DevOps Tooling and Sample Repository

### Sample Repository:
For this section, I’ve chosen a sample repository that demonstrates the application of essential DevOps tools and practices in a real-world context. This repository focuses on containerizing a simple **Rock-Paper-Scissor** game using **Docker** for consistent deployment and environment management.

[Sample Repository: DevOps Tooling Demonstration](https://github.com/Nvm-seff/Rock-Paper-Scissor)

# Rock-Paper-Scissors Game

## Overview

This repository contains the code for the **Rock-Paper-Scissors** game, a simple web-based application where players can play against the computer. The application has been containerized using **Docker** and deployed using **Kubernetes** to ensure scalability and consistent environments across development and production.

## Features

- **User Interface**: A simple, intuitive interface where users can select Rock, Paper, or Scissors to play against the computer.
- **Game Logic**: Implements the classic rules of Rock-Paper-Scissors.
- **Containerized with Docker**: The app is packaged in a Docker container, ensuring that it runs consistently across different environments.
- **Deployed on Kubernetes**: The app is deployed on a Kubernetes cluster for automated deployment, scaling, and management.

## Tools and Technologies Used

- **Node.js**: The backend of the application is built using Node.js.
- **Express**: Used for handling HTTP requests and routing.
- **Socket.io**: Enables real-time communication for multiplayer gameplay.
- **Docker**: Used to containerize the application and create a Docker image for easy deployment.
- **Kubernetes**: Used to deploy and manage the application in a scalable and resilient way.

## DevOps Tooling

The repository includes:
- **Docker containerization** for ensuring consistent environments across development and production.
- A **Docker image** that can be easily built and run.
- **Kubernetes deployment** for orchestrating and managing the app in a scalable and resilient way.

### Applying DevOps Tooling:
In this section, I apply the knowledge I’ve gained to enhance and automate the development lifecycle. I've worked on **Docker** for containerization and **Kubernetes** for deploying and managing the application, ensuring that the game runs consistently and can scale easily.

#### Tools Used:
- **Docker**: Ensures consistent environments for application development and deployment, simplifying setup and execution.
- **Kubernetes**: Used for automating the deployment, scaling, and management of the application. Kubernetes ensures that the app is highly available, easily manageable, and scalable across different environments.

## Expanding My Knowledge

Throughout this project, I have significantly expanded my knowledge of DevOps practices by diving deep into the following areas:

- **Containerization**: Using **Docker**, I containerized the Rock-Paper-Scissor game, allowing it to run seamlessly across different environments without the "it works on my machine" problem.
- **Docker Images**: I learned to build a Docker image for the application, enabling quick setup and deployment.
- **Kubernetes Deployment**: I implemented Kubernetes deployment files (`deployment.yaml` and `service.yaml`) to manage the application on a Kubernetes cluster, ensuring that the application is deployed in a scalable, fault-tolerant manner.
- **NodePort Service in Kubernetes**: I set up a **NodePort** service in Kubernetes to expose the application on a specific port across the cluster, making it accessible externally.
- **Simplified Setup and Execution**: With Docker and Kubernetes combined, I’ve made it easy to run, manage, and scale the application with minimal configuration using just a few commands.

## Prerequisites

To run this application locally or deploy it on your own Kubernetes cluster, you need the following:

- **Docker**: To build and run the application in a containerized environment.
- **Kubernetes**: To deploy and manage the application on a Kubernetes cluster.
- **kubectl**: The command-line tool for interacting with Kubernetes clusters.
- **Node.js**: Required to run the backend of the application.

## Sample CV

Please find my sample CV [here](https://drive.google.com/file/d/14Fp1KX_zQLAI0tQwddUdQm75ZQkMfV1X/view?usp=sharing), which includes details about my academic background, skills, and experience related to DevOps and software development.

## Contact

For any questions or further information, feel free to contact me via email at [saifullah.rizv@gmail.com].

---

Thank you for exploring my DevOps journey! I hope you find the materials helpful. Your feedback is highly appreciated!
