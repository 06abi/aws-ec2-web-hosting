# 🌐 AWS EC2 Static Website Hosting Project

## ✅ Project Overview

This project demonstrates how to deploy a static HTML website using an Amazon EC2 instance with Apache Web Server.

## 🛠️ Technologies Used

- AWS EC2
- Amazon Linux 2023
- Apache HTTP Server
- SCP & SSH
- HTML, CSS

## 🚀 Steps Followed

1. Launched EC2 instance with Amazon Linux
2. Installed Apache server
3. Allowed HTTP traffic in the security group
4. Transferred `index2.html` from local to EC2 using SCP
5. Placed the file in `/var/www/html` to host it
6. Accessed via public IP: `http://<your-ec2-ip>`

## 🔒 Optional Improvements

- Add SSL using Certbot for HTTPS
- Connect a custom domain using Route 53

## 📸 Screenshots

(Insert screenshots using GitHub upload button)

## 📚 Learnings

- Cloud server setup and hosting
- Apache installation and file management on Linux
- Secure remote connection using SSH and key pairs
