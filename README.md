# AWS High Availability Web Application

## 📌 Project Overview

This project demonstrates the deployment of a web application on AWS using Amazon EC2, Apache Web Server, AMI, Launch Template, Classic Load Balancer, Auto Scaling Group, Amazon SNS, and CloudWatch.

The project focuses on improving application availability, scalability, monitoring, and email notifications.

---

## 🏗️ AWS Services Used

* Amazon EC2
* Amazon Machine Image (AMI)
* Launch Template
* Classic Load Balancer (CLB)
* Auto Scaling Group (ASG)
* Amazon CloudWatch
* Amazon SNS
* Default Security Group

---

## ⚙️ Implementation Steps

### Step 1: Launch EC2 Instance

Created an Amazon EC2 instance to host the web application.

### Step 2: Connect to EC2

Connected to the EC2 instance using the AWS Console.

### Step 3: Install Apache Web Server

Installed and configured the Apache web server on the EC2 instance.

### Step 4: Test Web Page

Accessed the web page using the EC2 instance's public IP address.

### Step 5: Create AMI

Created an Amazon Machine Image (AMI) from the configured EC2 instance.

### Step 6: Create Launch Template

Created a Launch Template using the AMI configuration.

### Step 7: Create Classic Load Balancer

Created a Classic Load Balancer (CLB) to distribute incoming traffic.

### Step 8: Create Auto Scaling Group

Created an Auto Scaling Group (ASG) using the Launch Template.

### Step 9: Verify Auto Scaling

Verified that the Auto Scaling Group was working correctly.

### Step 10: Create SNS Topic

Created an Amazon SNS topic for sending notifications.

### Step 11: Subscribe Email

Subscribed an email address to the SNS topic.

### Step 12: Create CloudWatch Alarm

Created a CloudWatch alarm to monitor CPU utilization.

### Step 13: Verify Email Notification

Verified the email notification sent through Amazon SNS when the CloudWatch alarm was triggered.

---

## 📸 Screenshots

Project screenshots are available in the [`screenshots`](./screenshots) folder.

---

## 🚀 Key Features

* Web application hosting using EC2
* Load balancing using Classic Load Balancer
* Automatic scaling using Auto Scaling Group
* Infrastructure monitoring using CloudWatch
* Email notifications using SNS

---

## 🛠️ Technologies Used

* AWS
* Linux
* Apache Web Server

---

## 👩‍💻 Author

**Abinaya M**

Aspiring Cloud Engineer

## 📸 Project Screenshots

### EC2 Instance
![EC2 Instance](screenshots/01-ec2-instance.png)

### Apache Web Server
![Apache Web Server](screenshots/02-apache-web-server.png)

### Web Page Test
![Web Page Test](screenshots/03-webpage-test.png)

### AMI Creation
![AMI Creation](screenshots/04-ami-creation.png)

### Launch Template
![Launch Template](screenshots/05-launch-template.png)

### Classic Load Balancer
![Classic Load Balancer](screenshots/06-classic-load-balancer.png)

### Auto Scaling Group
![Auto Scaling Group](screenshots/07-auto-scaling-group.png)

### SNS Topic
![SNS Topic](screenshots/08-sns-topic.png)

### Email Subscription
![Email Subscription](screenshots/09-email-subscription.png)

### CloudWatch Alarm
![CloudWatch Alarm](screenshots/10-cloudwatch-alarm.png)

### Email Notification
![Email Notification](screenshots/11-email-notification.png)
