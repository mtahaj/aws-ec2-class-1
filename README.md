# AWS EC2 — Class 1 Cloud Server Deployment

## Project Overview

This project demonstrates how to launch and configure an Amazon EC2 instance and deploy a simple static website using Ubuntu Linux and Nginx.

It was completed as part of Class 1: AWS EC2 Setup and Cloud Server Launch (16 November 2026).

## Technologies Used

- Amazon Web Services (AWS)
- Amazon EC2 (t3.micro)
- Ubuntu Server 24.04 LTS
- Nginx Web Server
- HTML and CSS
- SSH (Secure Shell)
- Amazon EBS

## Implementation Steps

1. Created an AWS EC2 instance using Ubuntu 24.04 LTS.
2. Configured an SSH key pair for secure authentication.
3. Configured security group rules for SSH (port 22) and HTTP (port 80).
4. Connected to the EC2 instance using SSH from Windows PowerShell.
5. Updated Ubuntu packages.
6. Installed and started the Nginx web server.
7. Created and deployed a custom HTML webpage.
8. Verified the website using the EC2 public IPv4 address.

## Learning Outcomes

Through this project, I learned how cloud servers operate, how to manage remote Linux instances, how SSH authentication works, and how security groups control network traffic.

I also gained practical experience deploying a static website on AWS infrastructure.

## Screenshots

Screenshots of the EC2 instance, SSH connection, and deployed webpage are included in the `screenshots` folder.

## Security Considerations

- SSH access was restricted to a specific public IPv4 address.
- HTTP access was enabled for the demonstration website.
- Private SSH keys and AWS credentials are not stored in this repository.

## Note

This is an educational deployment using HTTP. A production website should use HTTPS and appropriate security controls.
