# Kubernetes Deployment Project - VProfile Web Application

## Project Overview

In this project, we will deploy a multitier web application stack using Kubernetes. The web application, VProfile, has been containerized in previous projects, and now it's time to host it for production using Kubernetes as our container orchestration tool.

## Project Situation

We already have a containerized multitier web application stack - VProfile. The goal now is to deploy it for production on a Kubernetes cluster. Running containers for production requires considerations for high availability, fault tolerance, scalability, platform independence, and portability.

## Why Kubernetes?

Kubernetes is chosen as the container orchestration tool for its maturity, reliability, and widespread adoption. It provides high availability, auto-healing, easy scaling, and the flexibility to run containers on various environments seamlessly.

## Requirements

1. **Kubernetes Cluster:** Set up a Kubernetes cluster using Kops. 
2. **Containerized Application:** Ensure the vprofile application is containerized for containerizing the vprofile application.
3. **EBS Volume:** Create an EBS volume for the MySQL container to store persistent data.

## Project Steps

1. **Create Kubernetes Cluster:**
   - Use Cops to launch a production-grade Kubernetes cluster. 

2. **Prepare Containerized Application:**
   - Make sure the vprofile application is containerized with the required images.

3. **Create EBS Volume:**
   - Create an EBS volume to be used by the MySQL container for persistent data.

4. **Label Nodes:**
   - Label nodes with zone names to ensure pods run in the same zone as the EBS volume.

5. **Write Kubernetes Definition Files:**
   - Create Kubernetes definition files for deployment, service, secret, and volume.

6. **Deploy on Kubernetes:**
   - Use the kubectl command to apply the Kubernetes definition files and deploy the vprofile web application.

## Getting Started

Ensure you have a Kubernetes cluster set up using Cops, the vprofile application containerized, and the necessary EBS volume created. If not, refer to the specific projects mentioned above.

