# Devops-Course-2024
This Repo will walk through some details about what we learned in Devops course 2024 taught by @Saim Safdar
## What i Have Learned
<ul>
  <li>Github</li>
  <li>Docker</li>
  <li>Podman</li>
  <li>Kubernetes</li>
  <li>Ingress</li>
  <li>Istio</li>
  <li>ECS/EKS</li>
  <li>Infrastructure as code</li>
  <ul>
    <li>Terraform</li>
    <li>Pulumi</li>
  </ul>
  <li>Policy as code</li>
  <ul>
    <li>Kyverno</li>
  </ul>
  <li>Knative</li>
</ul>

## Summarizing Blogs

### Blog 1: The New Horizon: Exploring Podman’s Container Evolution
In the reign of Devops, Docker plays a vital role in managing, running and maintaining containers. Containers are running form of Images, whereas images are snapshot of working code at some time. We can spun up more than one container from Docker image, which is directed by Dockerfile. Docker Desktop is the application running in local system which helps in creating images, running containers and maintaining them. Docker Desktop uses running server or Daemon which listens to client requests and managing API calls to Dockerhub. Thats where Podman comes in, it follows serverless archietecture and also do not require Dockerfile for additional configurations. Podman having serverless archietecture with no root access, integration with buildah for configuring images, high level security and reliance with docker containers and other tools are some strong features giving tough time to Docker.

### Blog 2: Pulumi: Turn Complex Infrastructure into Code with Ease
Infrastructure as code is a technique of writing code for provisioning of infrastructure on cloud. This makes the provisioning, maintaining and automating the infrastructure such EKS and EC2 by providing programmatic configuration files. Terraform and Pulumi are two big names in this region. Terraform is created by Hashicorp and uses Hashicorp configuration language (HCL) which is easily understandable. It uses terraform init, terraform plan and terraform apply in sequence for setting the whole process. On the other hand pulumi uses common programming language for writing configuration files. This saves time of learning a new language. Pulumi utilizes the cloud for storing state, hence the secret is saved on cloud in an encrypted form. It is in the same language as the application so it can be embedded in the code for easy testing and also can be reused utilizing classes and methods.

### Deployed Resource:
**DockerHub Link:** https://hub.docker.com/r/talhashahzad0/instaclone
<br>
**Github Link:** https://github.com/talha-shahzad/Djnago-Instagram-Clone
