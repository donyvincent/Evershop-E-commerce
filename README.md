# Evershop-E-commerce

📌 Project Overview

This repository documents the complete deployment of the EverShop E-commerce platform on a fully scalable AWS cloud architecture.
EverShop is a modern Node.js-based e-commerce framework offering a storefront and an admin panel.
This project demonstrates production-ready cloud deployment practices including:
Scalable compute
Managed databases
Global CDN delivery
Secure HTTPS domain routing
High availability architecture
This deployment covers both business functionality and cloud infrastructure engineering.



*******************🚀 Features Implemented*******************


Compute & Scaling
*Deployed EverShop (Node.js) on Amazon EC2
*Configured Launch Templates and Auto Scaling Group
*Integrated Application Load Balancer (ALB) for high availability

Database Layer
*Amazon RDS MySQL → Stores business/product/customer data
*PostgreSQL → Stores internal EverShop system metadata

Storage & CDN
*Amazon S3 for product image uploads
*CloudFront CDN for global, low-latency delivery of images

Networking & Security
*Route 53 custom domain routing
*ACM SSL Certificate enabling HTTPS
*Configured IAM roles & security groups for secure communication
*ALB → EC2 health checks + auto-healing

Customization Performed
*Fully implemented and tested the Electronics product category
*Added sample products, uploaded images, validated admin workflows
*Optimized static asset delivery via CloudFront



**********************⚙️ Tech Stack**********************



AWS Services
*EC2 · Auto Scaling · ALB · RDS (MySQL) · PostgreSQL · S3 · CloudFront · Route 53 · ACM · IAM

Application Stack
*Node.js · EverShop · PM2 · Nginx (optional reverse proxy)



***************📝 Deployment Summary***************


✔ 1. Launch EC2 & Deploy EverShop
*Installed Node.js, PM2
*Installed EverShop and configured .env
*Connected MySQL + PostgreSQL
*Started production build

✔ 2. Configure RDS MySQL
*Created DB instance
*Created EverShop tables
*Connected via environment variables

✔ 3. Configure S3 + CloudFront
*Enabled public-blocking bucket
*Created CloudFront distribution
*Updated EverShop config with baseUrl

✔ 4. Configure Networking
*Created ALB → Target Group → Health checks
*Created Auto Scaling Group
*Added Route 53 domain
*Requested ACM SSL → Attached certificate




************************👨‍💻 Electronics Category Customization**************************



As part of training, the Electronics category was fully implemented:
*Added products
*Uploaded images to S3
*Verified CloudFront delivery
*Tested storefront and admin panel
*Ensured workflow functionality (create → view → update → delete)





**********************🎯 Outcome****************************

This project demonstrates the ability to:
*Deploy production-level cloud architectures
*Integrate multiple AWS services
*Manage multi-database applications
*Optimize performance using CDN & caching
*Secure applications with HTTPS
*Troubleshoot cloud and backend issues
*Apply real-world DevOps practices

