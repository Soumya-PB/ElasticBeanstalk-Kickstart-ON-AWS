# 🚀🌱 Elastic Beanstalk Kickstart

A beginner-friendly AWS project demonstrating how to deploy a sample web application using **AWS Elastic Beanstalk** with a **Single Instance** environment.

---

## 📌 Project Overview

This project demonstrates how AWS Elastic Beanstalk simplifies application deployment by automatically provisioning the required infrastructure. Instead of manually creating and configuring an EC2 instance, Elastic Beanstalk handles the deployment process and provides a public URL to access the application.

---

## 🎯 Objective

- Learn the basics of AWS Elastic Beanstalk.
- Deploy the AWS Sample Application.
- Understand how Elastic Beanstalk automatically creates and manages an EC2 instance.
- Access the deployed application through the Environment URL.

---

## 🛠️ AWS Services Used

- AWS Elastic Beanstalk
- Amazon EC2
- AWS IAM
- Amazon CloudWatch

---

## 🏗️ Architecture

```
User
   │
   ▼
Elastic Beanstalk Environment URL
   │
   ▼
Elastic Beanstalk
   │
   ▼
Amazon EC2 (Single Instance)
   │
   ▼
Sample Web Application
```

---

## 🚀 Deployment Steps

### Step 1: Open AWS Elastic Beanstalk
- Sign in to the AWS Management Console.
- Search for **Elastic Beanstalk**.
- Open the service.

### Step 2: Create an Application
- Click **Create Application**.
- Enter the application name.
- Choose the desired platform.
- Select **Sample Application**.

### Step 3: Configure the Environment
- Select **Single Instance** as the environment type.
- Keep the default settings.
- Create the environment.

### Step 4: Deployment
- Elastic Beanstalk automatically:
  - Creates one EC2 instance.
  - Deploys the sample application.
  - Configures the environment.
  - Monitors the application health.

### Step 5: Access the Application
- Wait until the environment status changes to **Healthy**.
- Open the generated **Environment URL**.
- Verify that the Sample Application is running successfully.

---

## 📂 Project Workflow

```
Create Application
        │
        ▼
Select Sample Application
        │
        ▼
Create Single Instance Environment
        │
        ▼
Elastic Beanstalk Launches EC2
        │
        ▼
Application Deployment
        │
        ▼
Access Environment URL
```

---

## 📖 What I Learned

- Creating an AWS Elastic Beanstalk application.
- Deploying the AWS Sample Application.
- Understanding the Single Instance deployment model.
- Learning how Elastic Beanstalk automatically provisions an EC2 instance.
- Accessing applications through the Environment URL.
- Monitoring application health using CloudWatch.

---

## ✅ Features

- Easy application deployment
- Automatic EC2 provisioning
- Simple environment management
- Built-in health monitoring
- Beginner-friendly AWS deployment

---

## 📸 Output

> Successfully deployed the AWS Elastic Beanstalk Sample Application using a Single EC2 Instance and accessed it through the generated Environment URL.

---

## 📚 Technologies Used

- AWS Elastic Beanstalk
- Amazon EC2
- AWS IAM
- Amazon CloudWatch

---
