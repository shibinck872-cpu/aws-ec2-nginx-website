# AWS EC2 Nginx Website

## Project Description
This project demonstrates deploying a simple HTML website on an AWS EC2 Ubuntu instance using the Nginx web server.

## Live Demo

Website accessible through the EC2 Public IP:

**http://65.0.21.16

## AWS Services Used
- Amazon EC2
- Security Group
- Key Pair

## EC2 Setup Steps

1. Launched an Ubuntu 24.04 EC2 instance.
2. Created a Key Pair.
3. Configured Security Group to allow:
   - SSH (22)
   - HTTP (80)
4. Connected to the EC2 instance using SSH.
5. Updated the package list.
6. Installed Nginx.
7. Verified that Nginx was running.
8. Replaced the default Nginx page with a custom HTML page.
9. Accessed the website through the EC2 Public IP.

## Linux Commands Used

```bash
sudo apt update
sudo apt install nginx -y
sudo systemctl status nginx
sudo systemctl restart nginx
sudo nano /var/www/html/index.html
df -h
free -h
ps aux
```

## Website Details

- Name: Shibin CK
- College: Srinivas University
- Branch: BCA (AI, CC & DevOps)
- Email: shibinck872@gmail.com
- Web Server: Nginx

## Evidence

The following evidence is included in the submission:

- EC2 instance running
- SSH connection established
- Nginx service running
- Website accessible through the EC2 Public IP
- Docker `hello-world` container executed successfully 

## Repository Contents
```
.
├── index.html
└── README.md
```

## Outcome
Successfully deployed a custom HTML website on AWS EC2 using the Nginx web server and verified that it is accessible through the EC2 Public IP.

## Bonus Task

Installed Docker on the EC2 instance and verified the installation by running the official `hello-world` container.

### Commands Used

```bash
sudo apt install docker.io -y
docker --version
sudo docker run hello-world
```

### Result

Docker was successfully installed and the `hello-world` container executed successfully, confirming that the Docker Engine is working correctly.

## Author
Shibin CK
