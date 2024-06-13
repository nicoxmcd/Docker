# [Docker & Kubernetes: The Practical Guide [2024 Edition]](https://www.udemy.com/share/103IaC3@5G0-SQ_L9ghBhMFLdnkrUZJAl7q2eUVI4A234q8Y8LLcBmRGKWcDhkGKGDXmx6wVEA==/)

I'm currently utilizing this course from Udemy created by Maximilian Schwarzmüller, here is the following description for the course if anyone would also like to take it! 

Docker & Kubernetes are amongst the most in-demand technologies and topics you can learn these days. Because they significantly simplify the development and deployment process of both simple and complex software projects. 
For modern DevOps (Development Operations) but also for local development - on your own or in a team - this is a winner feature since you will no longer have any "but it worked on my machine" discussions. It works inside of a container, hence it works everywhere!

## In detail, the course includes the following topics:
- A thorough introduction to Docker, containers and why you might want to use Docker
- Detailed setup instructions for macOS and Windows
- A deep-dive into the core concepts you need to know: Containers & images
- Learn how to create custom images, use existing images and how to run containers based on such images
- Get a detailed overview of the core commands you need when working with Docker
- Learn how to work with data and how to persist data with volumes
- Explore container networking - with the outside world and between multiple containers
- Learn how to work with both single and multi-container projects
- In-depth deployment instructions: Manual deployment and deployment with managed services like AWS ECS
- Understand Kubernetes core concepts & architecture
- Learn how to create Kubernetes resources, deployments, services and how to run your containers with Kubernetes
- Dive deeply into working with data in Kubernetes projects - with different types of volumes
- Kubernetes networking and DNS service discovery
- Learn how to deploy your Kubernetes project (at the example of AWS EKS)

## What I'm learning
- Learn what Docker and Kubernetes are and why you might want to use them
- Learn how to install and use Docker on any system (macOS, Windows, Linux)
- Learn how to create and use Images & Containers with Docker
- Understand complex topics like managing and persisting data with Volumes
- Learn about Container Networking with Docker Networks and DNS Service Discovery
- Learn how to deploy Docker applications - manually, with managed services or with Kubernetes

## Setup Docker Desktop for Windows 
To check which version of Windows you are running you can open `Settings >> System >> About >> Windows Specifications`. Since I am utilizing Windows 11 Pro, then I will only need to follow a few steps to install Docker Desktop. Docker is not natively supported on Windows which is why there are some steps you need to follow before installation. If you are running an earlier version of Windows and or (the version is Windows Home there are other instructions you will need to follow)[https://learn.microsoft.com/en-us/windows/wsl/install].
![My specifications for Windows](https://github.com/nicomcd/Docker/assets/35404943/ebed0b4e-aaa9-45df-8fc6-48286c1ec9b9)
Then I can open `Windows Powershell` and `Run as Adminstrator` and enable Hyper-V by running the following command:
```
Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Hyper-V -All
```
Enable Containers Feature with the following command:
```
Enable-WindowsOptionalFeature -Online -FeatureName containers –All
```
Afterwards, we can install (Docker Desktop from the website)[https://www.docker.com/products/docker-desktop/]:
![Docker](https://github.com/nicomcd/Docker/assets/35404943/90228874-c9dd-49ae-9194-561d081b8aed)
Once it is finished installing you can leave the setting ticked for WSL 2 and follow through the installation prompts. Then you can make a Docker account; I made one as a Student and follow some of the tutorials or utilize the same course I'm using.

