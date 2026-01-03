# Cloud-Deployed Full-Stack Task Management Application (AWS)

## Project Overview
This project is a cloud-deployed full-stack web application designed to manage user tasks.
The application demonstrates real-world cloud deployment using core AWS services and follows a scalable and secure architecture.

The frontend is hosted using AWS S3 and CloudFront, the backend is deployed on an AWS EC2 instance using Python Flask, and the database is managed using AWS RDS (MySQL).

---

## Architecture Overview
Frontend (HTML/CSS/JS)
→ AWS S3 (Static Website Hosting)
→ AWS CloudFront (CDN)

Backend (Python Flask REST API)
→ AWS EC2 (Linux Instance)

Database
→ AWS RDS (MySQL)

Monitoring & Security
→ AWS CloudWatch
→ AWS IAM & Security Groups

---

## AWS Services Used
- AWS S3 – Static frontend hosting
- AWS CloudFront – Content Delivery Network
- AWS EC2 – Backend API hosting
- AWS RDS (MySQL) – Managed relational database
- AWS IAM – Access control and permissions
- AWS CloudWatch – Monitoring and performance metrics

---

## Features Implemented
- User login and task management functionality
- RESTful backend APIs for task operations
- Persistent data storage using MySQL RDS
- Secure EC2 access via SSH key pairs
- CloudWatch monitoring for system reliability

---

## Project Status
Core cloud infrastructure and deployments are live.
Backend APIs and database integration are functional.
Additional feature enhancements and UI improvements are planned.

---

## How to Run (High-Level)
1. Frontend is accessible via S3/CloudFront public URL.
2. Backend APIs are deployed on EC2 and exposed via public IP.
3. Database is hosted on AWS RDS and connected securely to EC2.

---

## Learning Outcomes
- Hands-on experience with AWS core services
- Understanding of cloud-based application architecture
- Practical exposure to deployment, security, and monitoring
- Real-world full-stack cloud development workflow
