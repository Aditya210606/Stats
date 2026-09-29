# Experiment 07 – Kubernetes Container Deployment and Management

**Title** - Deploy and Manage Containers using Kubernetes

 **Aim** - To deploy, manage, and scale containerized applications using **Kubernetes** and understand the basic concepts of container orchestration.

**Objectives** - After completing this experiment, the following objectives were achieved:

1. Understood the basic concepts of Kubernetes and container orchestration.
2. Installed and configured a Kubernetes environment.
3. Created and deployed a containerized application.
4. Managed Kubernetes Pods and Deployments.
5. Exposed the application using a Kubernetes Service.
6. Observed and managed the running application using Kubernetes commands.

**Tools and Technologies Used**

* Kubernetes
* Docker
* Ubuntu
* kubectl
* Minikube
* YAML

**Methodology**

The experiment follows the workflow:

```text
Kubernetes Installation
        ↓
Cluster Initialization
        ↓
Container Image
        ↓
Deployment Configuration
        ↓
Pod Creation
        ↓
Service Configuration
        ↓
Application Deployment
        ↓
Application Management
```

**Procedure**

1. Install and configure Kubernetes and the required tools.
2. Start the Kubernetes cluster using Minikube.
3. Verify the cluster status using `kubectl`.
4. Create a Kubernetes Deployment configuration.
5. Deploy the containerized application.
6. Check the created Pods and their status.
7. Create a Kubernetes Service to expose the application.
8. Verify the Service and running application.
9. Use Kubernetes commands to inspect and manage the deployed resources.

**Kubernetes Components**

**Pod**

A Pod is the smallest deployable unit in Kubernetes. It contains one or more containers that run together.

**Deployment**

A Deployment manages Pods and ensures that the required number of application instances are running.

**Service**

A Service provides a stable way to access Pods and allows applications running inside the Kubernetes cluster to be exposed.

**kubectl**

`kubectl` is the command-line tool used to communicate with and manage Kubernetes clusters.

**Container Deployment**

The application was deployed as a container inside the Kubernetes cluster. Kubernetes created and managed the required Pods through the Deployment configuration.

The status of the Pods and Services was checked using Kubernetes commands to verify that the application was running correctly.

**Results**

The experiment successfully:

* Installed and configured the Kubernetes environment.
* Started a Kubernetes cluster.
* Created a containerized application deployment.
* Created and managed Kubernetes Pods.
* Configured a Kubernetes Service.
* Verified the status of the deployed application.
* Used `kubectl` commands to manage Kubernetes resources.

**Conclusion**

The experiment demonstrated the basic use of Kubernetes for container orchestration. A containerized application was successfully deployed and managed using Kubernetes Deployment, Pods, and Services. The experiment provided an understanding of how Kubernetes simplifies the deployment and management of containerized applications.

---

**Screenshots**

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/e0abb3bb-d926-4f3a-a3c4-61d6ad3614b0" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/9502d0ac-0740-41cc-8844-97da8a2d752a" />

