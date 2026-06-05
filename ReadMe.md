#  Build a Database Server (AWS)

## Author

### Name: Mohamed Zabir Khan A
### Register Number: 212224230162

---

## Objective

The objective of this experiment is to understand how to deploy and configure a database server in AWS. This lab focuses on launching an EC2 instance, installing a database management system (DBMS), configuring basic database settings, creating a sample database, and validating connectivity to the database server.

---

## Prerequisites

* Basic understanding of cloud computing concepts
* AWS account or AWS Academy Lab access
* An existing VPC and EC2 knowledge (from previous labs)
* Basic knowledge of Linux commands and SQL

---

## Tools Used

* AWS Management Console
* Amazon EC2
* Security Groups
* SSH Client (Terminal / PuTTY)
* MySQL / MariaDB / PostgreSQL (any one)

---

## Tasks Performed

### Task 1: Launch EC2 Instance for Database Server

Launch a new EC2 instance using Amazon Linux 2 AMI. Select an appropriate instance type and configure key pair and security group.

---

### Task 2: Configure Security Group for Database Access

Modify the security group to allow:

* SSH (Port 22) for remote access
* Database port (e.g., MySQL – 3306 or PostgreSQL – 5432)

---

### Task 3: Connect to EC2 Instance

Connect to the EC2 instance using SSH from your local machine.

---

### Task 4: Install Database Server

Install a database server software such as MySQL, MariaDB, or PostgreSQL on the EC2 instance using package manager commands.

---

### Task 5: Start and Configure Database Service

Start the database service and configure basic settings such as root password and user privileges.

---

### Task 6: Create a Sample Database

Create a sample database and a table inside it. Insert a few records into the table.

---

### Task 7: Test Database Connectivity

Test the database server by connecting to it locally or remotely and performing basic SQL queries.

---

## Workflow (Student Explanation)

1. Launch an EC2 instance using Amazon Linux 2 AMI and select a suitable instance type. Configure key pair and security group to prepare the instance for database server deployment.
2. Modify the Security Group to allow:

SSH (Port 22) for remote login

Database port (3306 for MySQL / 5432 for PostgreSQL)
This ensures secure access to the database server.

3. Connect to the EC2 instance using SSH and install a database server such as MySQL, MariaDB, or PostgreSQL using package manager commands.
4. Start the database service, configure root credentials, and set user privileges. Create a sample database, table, and insert records to prepare the system for usage.
5. Test the database by connecting locally or remotely and executing basic SQL queries. This confirms that the database server is functioning correctly.

---

## Output Screenshots (Attach 3)

### Screenshot 1: EC2 Instance for Database Server

<img width="1265" height="552" alt="image" src="https://github.com/user-attachments/assets/92b4d5a8-894a-4549-a6f9-44eade64cbaa" />

---

### Screenshot 2: Database Service Running

<img width="1260" height="547" alt="image" src="https://github.com/user-attachments/assets/a3168c7a-a4c8-4867-9d8d-b223f3422502" />

---

### Screenshot 3: Sample Database and Table

<img width="1916" height="957" alt="Screenshot 2026-03-17 104504" src="https://github.com/user-attachments/assets/26258aa8-cb2f-4502-b2ec-46d502df82a8" />

---

## Result

This experiment demonstrated how to build a database server in AWS using an EC2 instance. By installing and configuring a DBMS, creating a sample database, and testing connectivity, the fundamentals of hosting and managing a cloud-based database server were understood.
