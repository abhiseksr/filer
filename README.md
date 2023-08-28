# WebApp Deployment using Kubernetes

This repository contains Kubernetes manifests for deploying the "FileInfo" application. The application is deployed as a single replica Deployment and exposed via a NodePort Service.

## Introduction

The Kubernetes manifests in this repository define a Deployment and a Service for the "WebApp" application. The Deployment ensures the application is available as a single replica, and the Service exposes it externally using a NodePort.

## Setup

1. Make sure you have a running Kubernetes cluster.

2. Clone this repository to your local machine:

   ```sh
   git clone https://github.com/abhiseksr/filer
   cd filer
   
## Running on Localhost

To run the application on your localhost for testing purposes, follow these steps:

1. Ensure you have `kubectl` configured to access your Kubernetes cluster.

2. Apply the Deployment and Service manifests:

   ```sh
   kubectl apply -f web-app.yaml

3. Access the application by finding the NodePort assigned to the Service:
   ```sh
   kubectl service webapp-service


