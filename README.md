# Deploy Microservices Application

![image](https://github.com/user-attachments/assets/47ea8898-585e-44e9-a5b9-cd88775d47de)



## **Project Overview**
**Online Boutique** is a cloud-first microservices demo application. Online Boutique consists of an 11-tier microservices application. The application is a web-based e-commerce app where users can browse items, add them to the cart, and purchase them.


---

## **Features**
- Created YAML file with 11 Deployment and corresponding Service manifests
- Configure the env variable and the end points (depending on if the service is talking to another service) for each microservice.
- Configure readiness and liveness probe on each microservice (Note; for application that required longer time to start up you can set InitiaDelaySeconds parameters)
- End point is servicename:service port
- Created a K8s cluster with 3 Worker Nodes on Linode
- Download the kubeconfig.yaml file to connect to the cluster.
- Set permission on the file using chmod 400 “file name”
- Set up the environmental variable using export in Linux and Set in windows
- Connected to the cluster
- Created a Namespace and deployed all the micro services into it.
- Deploy your application in the cluster (kubectl apply -f “file name”).
- Accessed Online Shop with Browser



## **Features**
- Created a Linode cluster

  ![image](https://github.com/user-attachments/assets/29ab5b29-fe39-4f8e-b442-d083aa8994f5)

  ![image](https://github.com/user-attachments/assets/f0cd3160-a676-428d-b460-205a41deb1ef)


  ![image](https://github.com/user-attachments/assets/8021b1df-f148-4ba9-aa0c-93456e0659e7)

  ![image](https://github.com/user-attachments/assets/bd8c7ded-787c-4751-857a-4a2428b8307d)

- Set permission for the kubeconfig file
  
  ![image](https://github.com/user-attachments/assets/67c5b901-6937-4918-9632-402c913acb44)

- Created a K8s cluster with 3 Worker Nodes on Linode
- Connected to the cluster
- Created a Namespace and deployed all the micro services into it

  ![image](https://github.com/user-attachments/assets/bae43744-ea7e-46f8-bd22-4deec6bf6d1c)


- Pods running in microservice namespace
  
  ![image](https://github.com/user-attachments/assets/a0df4032-be27-4423-ba94-a10451257dda)


- Accessed Online Shop with Browser
  ![image](https://github.com/user-attachments/assets/47ea8898-585e-44e9-a5b9-cd88775d47de)



## Screenshots

| Home Page                                                                                                         | Checkout Screen                                                                                                    |
| ----------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------ |
| [![Screenshot of store homepage](![image](https://github.com/user-attachments/assets/b68aa72f-483c-4192-8505-88661ddf1b3f) | [![Screenshot of checkout screen](![image](https://github.com/user-attachments/assets/dc5aee86-e641-4641-bbab-a1f51ed02173)
) |

