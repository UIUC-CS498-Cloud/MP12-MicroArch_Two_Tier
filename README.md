# MP12_MicroArch_Two_Tier

In this milestone project, you will deploy a cloud-based machine learning service that supports both a free and a premium tier. Each tier serves image classification tasks using different neural network models. You will use Amazon EKS, Docker, and Kubernetes to build, deploy, and manage your infrastructure, ensuring that resource usage is controlled and services are isolated.
The architecture follows a two-tier microservice design:
A Web Tier (Envoy proxy + Flask app) receives and routes requests.
A Service Tier handling corresponding services:
A Free service serves inference jobs (/free) using a simple feed-forward network.
A Premium service serves inference jobs (/premium) using a convolutional neural network.
This separation helps manage workloads, enforce resource quotas, and simulate a scalable SaaS offering.

![image](https://github.com/user-attachments/assets/70ec2ac6-76e9-4e04-915c-3927861d7e1f)
