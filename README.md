# From Local Files to GitHub: Uploading and Managing a Website Template with Basic AWS Exposure

## Project Overview

This project demonstrates how to transfer and deploy a random website template using GitHub and AWS services.

The main goal of this project is to understand:

- How to upload project files to GitHub
- How to transfer files to a cloud environment (AWS)
- Basic deployment of a static website

## Technologies Used

- Git & GitHub
- AWS (EC2 )
- Website Template

## Steps Performed

### 1. Upload to GitHub

- Initialized Git repository
- Added project files
- Pushed code to GitHub

### 2. AWS Setup

- Created AWS account
- Launched an EC2 instance using Amazon Linux 2023
- Configured security groups (allowed SSH - 22, HTTP - 80)
- Installed Git and Nginx on the EC2 instance
- Cloned the website template repository from GitHub
- Deployed the template files to the Nginx root directory
- Hosted the website on EC2 public IP

### 3. File Transfer

- Used Git to clone website repository from GitHub to EC2 instance

### 4. Deployment

- Configured web server (Nginx)
- Hosted the website

## Output

The website template is successfully deployed and accessible via AWS server.

## Learning Outcome

- Learned how to deploy a pre-built website template on AWS EC2
- Understood server configuration and hosting using Nginx
- Gained hands-on experience with GitHub and file transfer

---

## Author

Anisha Shelar
