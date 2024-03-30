# NetworkCA

# Ansible Playbook for Docker Container Deployment

This repository contains an Ansible playbook for automating the deployment of a Docker container running an Apache service.

## Overview

The Ansible playbook named `docker_deploy.yml` automates the deployment process, orchestrating the setup of an Apache Docker container. The playbook defines tasks to create a Docker network, pull the httpd image, and configure the container with Git installed. Upon execution, the container is connected to the specified Docker network and made accessible via port 8080 on the host machine.

## Prerequisites

Before running the playbook, ensure the following prerequisites are met:
- Ansible is installed on the control machine.
- Docker is installed on the target machine(s).

## Usage

1. Clone this repository:
   ```bash
   git clone https://github.com/your_username/ansible-docker-deployment.git
2. Navigate to the repository directory:
   cd ansible-docker-deployment
3. Edit the hosts file to specify the target host(s) where the Docker container will be deployed.
4. Run the Ansible playbook:
     ansible-playbook docker_deploy.yml


   Chandu Lavu

