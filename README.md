<h1 align="center">☁️ AWS High Availability Web Application</h1>

<p align="center">
Scalable and fault-tolerant web architecture deployed using AWS Cloud Services
</p>

<p align="center">
EC2 • Load Balancer • Target Group • AMI • Security Groups
</p>

---

## 🎯 Project Objective

To design and deploy a highly available web application on AWS ensuring:
- Scalability
- Fault tolerance
- Load balancing between multiple EC2 instances

---

## 🏗️ Architecture

User → Application Load Balancer → Target Group → EC2 Instances

---

## ☁️ AWS Services Used

- Amazon EC2 (Web Servers)
- Application Load Balancer (Traffic Distribution)
- Target Group (Health Monitoring)
- Amazon Machine Image (AMI)
- Security Groups (Firewall Rules)

---

## ⚙️ Implementation Steps

### 1️⃣ EC2 Setup
- Launched 2 EC2 instances
- Installed Apache web server

### 2️⃣ Web Deployment
- Created simple HTML pages for testing

### 3️⃣ Load Balancer Setup
- Created Application Load Balancer (ALB)
- Attached Target Group

### 4️⃣ Health Check Configuration
- Registered EC2 instances
- Verified instance health status

### 5️⃣ Testing
- Accessed ALB DNS
- Verified traffic distribution between servers

### 6️⃣ AMI Creation
- Created Amazon Machine Image (AMI)
- Used for reusable server deployment

---

## 📸 Screenshots

### EC2 Instances
![EC2](Screenshot 2026-05-18 095217.png)

### Web Server Output (Server 1)
![Web1](Screenshot 2026-05-18 095229.png)

### Web Server Output (Server 2)
![Web2](Screenshot 2026-05-18 095240.png)

### Target Group Health Status
![TG](Screenshot 2026-05-18 095310.png)

### Load Balancer DNS Output
![ALB](Screenshot 2026-05-18 095336.png)

### Final Application Output
![Final](Screenshot 2026-05-18 095402.png)

---

## 🚀 Key Learnings

- AWS EC2 instance lifecycle
- Load balancing and traffic distribution
- High availability architecture design
- Health checks and Target Groups
- AMI creation and reuse

---

## 📊 Outcome

Successfully deployed a production-style highly available web application on AWS Cloud.

---

## 👨‍💻 Author

**Avinash Patil**  
Cloud & DevOps Engineer (Aspiring)
