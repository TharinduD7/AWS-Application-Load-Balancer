# AWS Application Load Balancer (ALB)

## Project Overview

This project demonstrates how to configure and implement an **AWS Application Load Balancer (ALB)** to distribute incoming HTTP traffic across multiple Amazon EC2 web servers. The main objective is to improve application availability, reliability, and scalability by using load balancing and automated health checks.

The project involves creating an AWS VPC, launching EC2 instances in multiple Availability Zones, configuring target groups, and setting up an Application Load Balancer to manage incoming application traffic.

## Technologies & Services Used

- **Amazon EC2** – Hosting web server instances.
- **Application Load Balancer (ALB)** – Distributing incoming application traffic.
- **Target Groups** – Managing and registering EC2 instances.
- **Health Checks** – Monitoring the availability and health of web servers.
- **Amazon VPC** – Providing network infrastructure.
- **Security Groups** – Controlling inbound and outbound traffic.
- **Availability Zones** – Improving application availability.

## Key Features

- Distributed incoming HTTP traffic across multiple EC2 instances.
- Configured ALB listeners and target groups.
- Implemented health checks to monitor server availability.
- Automatically routed traffic away from unhealthy instances.
- Configured security groups for secure communication.
- Tested load balancing and traffic distribution.

## Project Architecture

Developer / Client → Application Load Balancer → Target Group → EC2 Web Server 1 & EC2 Web Server 2

## Learning Outcomes

Through this hands-on project, I gained practical experience in AWS networking, load balancing, EC2 instance management, target group configuration, health checks, and high-availability architecture.

## Project Status

Completed
