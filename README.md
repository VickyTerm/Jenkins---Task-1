# DevOps Website Project 🚀

## 📌 Overview
This project demonstrates a complete DevOps workflow using **AWS EC2**, **Docker**, **Jenkins**, and **Nginx**.  
The goal was to provision infrastructure, configure essential tools, and automate deployment pipelines with GitHub webhooks.

---

## ⚙️ Infrastructure Setup
- **EC2 Instance**: Free-tier Amazon EC2 instance  
  - Public Elastic IP: `18.61.193.75`  
  - Instance ID: `i-033867d75bdc18f63`
- **Elastic IP** ensures a static address for consistent access to the hosted application.

---

## 🛠️ Installed Software
- **Docker** → Containerization of applications for portability and scalability.
- **Jenkins** → CI/CD automation server for building and deploying pipelines.
- **Nginx** → Configured as a reverse proxy for networking and load balancing.

---

## 🔄 CI/CD Pipeline
- Jenkins pipeline successfully configured and executed.
- Automated builds and deployments triggered via **GitHub Webhooks**.
- Pipeline stages include:
  1. **Code Checkout** from GitHub.
  2. **Build & Test** using Docker.
  3. **Deployment** to EC2 instance.
  4. **Verification** through Nginx routing.

---

## 🌐 Repository
Project source code and configurations are available here:  
👉 [DevOps Website Repository](https://github.com/VickyTerm/Devops-Website.git)

---

## 📡 Access
- Application hosted on EC2: `http://18.61.193.75`
- Managed via Jenkins pipelines and automated triggers.

---

## ✅ Key Achievements
- Provisioned EC2 with Elastic IP for stable hosting.
- Installed and configured Docker, Jenkins, and Nginx.
- Successfully ran Jenkins pipelines with automated deployment.
- Integrated GitHub webhooks for seamless CI/CD automation.

---

## 📖 Future Improvements
- Add monitoring with **Prometheus + Grafana**.
- Implement Infrastructure as Code using **Terraform**.
- Enhance security with **SSL certificates** and IAM roles.

---

## 👨‍💻 Author
**VickyTerm**  
DevOps Enthusiast | Cloud Learner | Automation Explorer
