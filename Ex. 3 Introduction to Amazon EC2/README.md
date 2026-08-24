# Lab 3 – Introduction to Amazon Elastic Compute Cloud (EC2)

## Author

* **Name**: Junaid Sardar S
* **Register Number**: 212224100028
* **Date of Submission**: 24/08/2026

---

## Objective

The objective of this experiment is to understand the fundamentals of Amazon Elastic Compute Cloud (EC2). This lab focuses on launching and managing a virtual server, understanding instance types and AMIs, connecting to an EC2 instance, monitoring its status, and performing basic instance operations such as start, stop, and terminate.

---

## Prerequisites

* Basic understanding of cloud computing concepts
* AWS account or AWS Academy Lab access
* Web browser with internet connectivity
* Basic knowledge of Linux commands (optional)

---

## Tools Used

* AWS Management Console
* Amazon EC2
* Key Pair
* Security Group
* SSH Client (PuTTY / Terminal)

---

## Tasks Performed

### Task 1: Explore Amazon EC2 Dashboard

Explore the EC2 service dashboard in the AWS Management Console. Observe the different sections such as Instances, AMIs, Instance Types, Key Pairs, Security Groups, and Elastic IPs.

---

### Task 2: Launch an EC2 Instance

Launch a new EC2 instance using Amazon Linux 2 AMI. Select an appropriate instance type (t2.micro) under the free tier. Configure basic settings such as instance name, key pair, and security group.

---

### Task 3: Configure Security Group

Configure a security group to allow inbound access:

* SSH (Port 22) from your IP address
* HTTP (Port 80) from anywhere (0.0.0.0/0)

This security group acts as a firewall for the instance.

---

### Task 4: Connect to EC2 Instance

Connect to the running EC2 instance using SSH. Use the downloaded key pair and connect via terminal or PuTTY.

For Amazon Linux:

```
ssh -i "keyname.pem" ec2-user@<Public-IP>
```

---

### Task 5: Perform Basic Instance Operations

Perform the following operations from the EC2 console:

* Stop the instance
* Start the instance
* Reboot the instance

Observe the state changes of the instance.

---

### Task 6: Monitor EC2 Instance

Monitor the EC2 instance using the Monitoring tab. Observe metrics such as CPU utilization, network in/out, and instance status checks.

---

### Task 7: Terminate EC2 Instance

Terminate the EC2 instance after completing the experiment to avoid unnecessary AWS charges.

---

## Workflow (Student Explanation)

1. Explored the Amazon EC2 Dashboard and understood the different sections such as Instances, AMIs, Key Pairs, Security Groups, and Instance Types.
2. Launched an Amazon Linux EC2 instance by selecting the appropriate AMI, instance type, key pair, and security group.
3. Configured the Security Group to allow SSH access on port 22 and HTTP access on port 80.
4. Connected to the running EC2 instance using SSH and the key pair, and verified that the instance was accessible.
5. Performed basic instance operations such as Stop, Start, and Reboot, and observed the instance state changes.
6. Monitored the EC2 instance using the Monitoring tab and checked CPU utilization, network activity, and status checks.
7. Finally, terminated the EC2 instance after completing the experiment to avoid unnecessary AWS resource usage and charges.

---

## Output Screenshots (Attach 3)

### Screenshot 1: EC2 Dashboard / Instance List

![alt text](<Screenshot 2026-08-22 104401.png>)

---

### Screenshot 2: SSH Connection to Instance

![alt text](<Screenshot 2026-08-22 115402.png>)

---

### Screenshot 3: Instance Monitoring / Status

![alt text](<Screenshot 2026-08-22 115852.png>)

---

## Result 

This experiment provided hands-on experience with Amazon EC2 by demonstrating how to launch, connect, manage, and monitor a virtual server in AWS. It helped in understanding the concept of Infrastructure as a Service (IaaS) and how compute resources can be provisioned and controlled on demand in the cloud.
