# Helm-Demo-Managed-K8s-cluster


## **Project Overview**
**Online Boutique** is a cloud-first microservices demo application.
Online Boutique consists of an 11-tier microservices application. The application is a
web-based e-commerce app where users can browse items,
add them to the cart, and purchase them.
This project demonstrates deploying a managed K8s cluster on Linode Kubernetes engine, deployed a replicated database and configure its persistence and make it accessible through a UI client browser using ingress.

---

## **Features**
- Created K8s cluster on Linode Kubernetes Engine
- Deployed replicated MongoDB (StatefulSet using Helm Chart) and configured Data Persistence with Linode Block Storage
- Deployed MongoExpress (Deployment and Service)
- Deployed NGINX Ingress Controller as Loadbalancer (using Helm Chart)
- Configured Ingress rule



Google uses this application to demonstrate the use of technologies like
Kubernetes, GKE, Istio, Stackdriver, and gRPC. This application
works on any Kubernetes cluster, like Google
Kubernetes Engine (GKE). It’s **easy to deploy with little to no configuration**.

If you’re using this demo, please **★Star** this repository to show your interest!

**Note to Googlers (Google employees):** Please fill out the form at [go/microservices-demo](http://go/microservices-demo).

## Screenshots

| Home Page                                                                                                         | Checkout Screen                                                                                                    |
| ----------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------ |
| [![Screenshot of store homepage](![image](https://github.com/user-attachments/assets/b68aa72f-483c-4192-8505-88661ddf1b3f) | [![Screenshot of checkout screen](![image](https://github.com/user-attachments/assets/dc5aee86-e641-4641-bbab-a1f51ed02173)
) |

## Interactive quickstart (GKE)

[![Open in Cloud Shell](https://gstatic.com/cloudssh/images/open-btn.svg)](https://ssh.cloud.google.com/cloudshell/editor?cloudshell_git_repo=https%3A%2F%2Fgithub.com%2FGoogleCloudPlatform%2Fmicroservices-demo&shellonly=true&cloudshell_image=gcr.io/ds-artifacts-cloudshell/deploystack_custom_image)
