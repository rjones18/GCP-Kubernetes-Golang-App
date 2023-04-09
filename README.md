# GCP-Kubernetes-Python-App
In this project I deployed a containerized Golang application on to the Google Kubernetes Engine. I setup continuous deployment by linking Github repository to Cloud Source Repositories and added a Cloud Build Trigger to automatically builds and deploys an updated docker image to the Kubernetes cluster. I also used Google Domains to setup a custom domain name for my application. The Kubernetes Cluster was built using Terraform. Reference [this repo](https://github.com/rjones18/Terraform-Kubernetes-Engine).

Link to Website:(Currently not deployed)

The application is broken down into the architecture below:

![kubernetespython](https://github.com/rjones18/Images/blob/main/KubernetesApp.png)
