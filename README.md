# 🚀 CI/CD Pipeline with Jenkins, Docker & AWS EC2

## 📌 Project Overview
This project demonstrates a complete CI/CD pipeline implementation using Jenkins on AWS EC2.
The pipeline automatically builds and deploys a Dockerized web application whenever code is pushed to GitHub.

---

## 🏗 Architecture Flow

GitHub → Jenkins (Poll SCM) → Docker Build → Docker Container → AWS EC2 Deployment

---

## 🛠 Tools & Technologies Used

- AWS EC2 (Amazon Linux 2023)
- Jenkins
- Git & GitHub
- Docker
- Apache (httpd)
- Linux

---

## 🔥 Pipeline Stages

1. Clone Repository
2. Build Docker Image
3. Stop Existing Container
4. Deploy New Container

---

## 🌍 Deployment

Application deployed on AWS EC2 and exposed via port 8081.

---

## 💡 Key Learning Outcomes

- Implemented end-to-end CI/CD pipeline
- Automated Docker image build & deployment
- Configured EC2 Security Groups
- Integrated GitHub with Jenkins using Poll SCM
- Hands-on experience with container lifecycle management

---

## 👨‍💻 Author

Kamlesh Kishor Aglave
DevOps Enthusiast
