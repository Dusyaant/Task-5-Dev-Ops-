# AWS Task-1: Windows EC2 Instance Setup and System Info

## 🚀 Project Overview
This project demonstrates how to launch a Windows Virtual Machine (VM) on AWS EC2, connect to it securely using Remote Desktop Protocol (RDP), and retrieve detailed system information via the Command Prompt.

## 🛠️ Tech Stack
* **Cloud Provider:** AWS (Amazon Web Services)
* **Service:** EC2 (Elastic Compute Cloud)
* **Operating System:** Microsoft Windows Server 2022 Datacenter
* **Connection Tool:** Remote Desktop Connection (RDP)

## 📋 Steps Performed
1. **Instance Launch:** Configured a Windows Server instance on AWS EC2.
2. **Security Group Configuration:** Opened Port 3389 to allow RDP traffic.
3. **Password Decryption:** Used the `.pem` key pair to retrieve the Administrator password.
4. **RDP Connection:** Successfully logged into the remote Windows desktop.
5. **System Verification:** Ran the `systeminfo` command in CMD to capture hardware and network details.

## 🖼️ Verification Screenshots

### Part 1: OS and Processor Details
This screenshot confirms the OS version, Host Name, and CPU specifications.
![System Info Top](images/aws-windows-systeminfo-top.png)

### Part 2: Network and Memory Configuration
This screenshot details the RAM usage, Network Adapter (Amazon ENA), and Internal IP.
![System Info Bottom](images/aws-windows-systeminfo-bottom.png)

## 🛑 Post-Task Cleanup
To follow AWS best practices and avoid unnecessary charges, the instance was **Terminated** immediately after the task was completed.
