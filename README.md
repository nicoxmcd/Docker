# [Docker & Kubernetes](https://www.udemy.com/share/103IaC3@5G0-SQ_L9ghBhMFLdnkrUZJAl7q2eUVI4A234q8Y8LLcBmRGKWcDhkGKGDXmx6wVEA==/)

I'm currently utilizing this course from Udemy created by Maximilian Schwarzmüller, here is the following description for the course if anyone would also like to take it! 

## What I'm learning
- Learn how to create and use Images & Containers with Docker
- Understand complex topics like managing and persisting data with Volumes
- Learn about Container Networking with Docker Networks and DNS Service Discovery
- Learn how to deploy Docker applications - manually, with managed services or with Kubernetes

## Setup Docker Desktop for Windows 
To check which version of Windows you are running you can open `Settings >> System >> About >> Windows Specifications`. Since I am utilizing Windows 11 Pro, then I will only need to follow a few steps to install Docker Desktop. Docker is not natively supported on Windows which is why there are some steps you need to follow before installation. If you are running an earlier version of Windows and or [the version is Windows Home there are other instructions you will need to follow](https://learn.microsoft.com/en-us/windows/wsl/install).
![My specifications for Windows](https://github.com/nicomcd/Docker/assets/35404943/ebed0b4e-aaa9-45df-8fc6-48286c1ec9b9)
Then I can open `Windows Powershell` and `Run as Adminstrator` and enable Hyper-V by running the following command:
```
Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Hyper-V -All
```
Enable Containers Feature with the following command:
```
Enable-WindowsOptionalFeature -Online -FeatureName containers –All
```
Afterwards, we can install [Docker Desktop from the website](https://www.docker.com/products/docker-desktop/):
![Docker](https://github.com/nicomcd/Docker/assets/35404943/90228874-c9dd-49ae-9194-561d081b8aed)
Once it is finished installing you can leave the setting ticked for WSL 2 and follow through the installation prompts. Then you can make a Docker account; I made one as a Student and follow some of the tutorials or utilize the same course I'm using.

