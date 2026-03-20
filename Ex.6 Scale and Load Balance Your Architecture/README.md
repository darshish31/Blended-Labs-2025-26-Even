# Lab 6 – Scale and Load Balance Your Architecture

## Title

Scale and Load Balance Your Architecture
Author : DARSHINI B   
Reg no : 212224230051   
Date : 18/03/2026

---

## Objective

The objective of this lab is to understand how to design a scalable and highly available architecture on AWS using Auto Scaling and Elastic Load Balancing. This experiment focuses on distributing incoming traffic across multiple EC2 instances, automatically scaling resources based on demand, and validating fault tolerance.

---

## Prerequisites

* Basic knowledge of Amazon EC2 and VPC
* Completion of previous labs (IAM, EC2, EBS, Database Server)
* AWS Academy Lab access
* Stable internet connection

---

## Tools Used

* AWS Management Console
* Amazon EC2
* Elastic Load Balancer (ELB / ALB)
* Auto Scaling Groups (ASG)
* Amazon CloudWatch

---

## Tasks Performed

### Task 1: Review Existing Architecture

Students review the existing EC2-based application architecture created in previous experiments.

### Task 2: Create a Launch Template

Students create a launch template that defines the EC2 instance configuration including AMI, instance type, security group, and user data.

### Task 3: Create an Auto Scaling Group

Students create an Auto Scaling Group using the launch template and configure minimum, maximum, and desired instance capacity.

### Task 4: Configure an Application Load Balancer

Students create an Application Load Balancer and configure target groups for routing traffic to EC2 instances.

### Task 5: Register Auto Scaling Group with Load Balancer

Students attach the Auto Scaling Group to the target group of the load balancer.

### Task 6: Configure Scaling Policies

Students configure scaling policies based on CPU utilization using Amazon CloudWatch alarms.

### Task 7: Test Load Balancing and Scaling

Students test the setup by generating traffic and observing automatic scaling and load distribution.

---

## Workflow (To be filled by Student)

1.Launch multiple servers.

2.Deploy the application on each server.

3.Create a load balancer.

4.Add servers to the load balancer.

5.Configure auto-scaling.

6.Test load distribution.
---

## Output Screenshots 

<img width="1919" height="1028" alt="image" src="https://github.com/user-attachments/assets/9d0602e8-ceac-42e0-9dc0-f6870cfb298b" />
<img width="1919" height="1031" alt="image" src="https://github.com/user-attachments/assets/acfabb35-3e1d-45ab-92be-2441a5ab88c8" />
<img width="1919" height="1026" alt="image" src="https://github.com/user-attachments/assets/7152c979-2042-4734-b4c1-df94dc965573" />
<img width="1919" height="1029" alt="image" src="https://github.com/user-attachments/assets/15e23716-09ba-4dc6-971e-7924745bd632" />
<img width="1919" height="1023" alt="image" src="https://github.com/user-attachments/assets/da1b29da-bb98-44fd-96aa-70f3be5dfc01" />
<img width="1919" height="1081" alt="image" src="https://github.com/user-attachments/assets/124f7fa5-6292-4b7c-9c63-771c5bedbacf" />
<img width="1919" height="1028" alt="image" src="https://github.com/user-attachments/assets/9e75d921-ae9f-4863-ba31-f69d539f4dd7" />
<img width="1919" height="1030" alt="image" src="https://github.com/user-attachments/assets/173ac229-4a84-4450-a815-8f43649ab5d6" />

---


## Result

This experiment demonstrated how to build a scalable and fault-tolerant cloud architecture using Auto Scaling Groups and Elastic Load Balancing. The system automatically adjusted resources based on workload and ensured continuous service availability by distributing traffic across multiple instances.
