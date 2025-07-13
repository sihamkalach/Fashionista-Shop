# 👗 Fashionista-Shop

![AWS](https://img.shields.io/badge/Deployed%20on-AWS-FF9900?logo=amazon-aws&logoColor=white&style=flat-square)

Fashionista-Shop is a full-stack e-commerce platform for fashion products, featuring a personalized product recommendation system powered by machine learning.

The system uses **K-Means clustering** to provide intelligent product suggestions based on user search behavior and preferences, enhancing the shopping experience through relevant recommendations.

---
![Alt text](https://github.com/sihamkalach/Fashionista-Shop/blob/4d5db7bc595a00d334625d0a06fdbcc4352b0aec/fashionista-media/fashionista%20architecture.png)
---

## 📄 Project Documentation

📝 [Click here to view the full project report (PDF)](https://github.com/sihamkalach/Fashionista-Shop/blob/a7513e11f3e036b609f57f8c1a7d41e683c8c9fe/fashionista-media/FASHIONISTA%20Smart%20E-Commerce%20Platform%20Presentation.pdf)

---

## 📹 Demo Video

▶️ [Watch the demo on YouTube](https://www.youtube.com/watch?v=yMZOFSPpfcQ)

> In this video, we demonstrate the main features of Fashionista-Shop, including the product catalog, search, recommendations, and the checkout flow.

---

## 🛠️ Tech Stack

- **Frontend**: React.js
- **Backend**: Django + Django REST Framework
- **Machine Learning**: Scikit-learn (K-Means clustering)
- **Database**: PostgreSQL 
- **Hosting**: AWS 

---

## 🚀 Key Features

- 🔍 Smart product search
- 🤖 ML-based product recommendations
- 👤 User authentication & shopping history
- 🛒 Shopping cart & checkout system
- 📱 Responsive design

---

## ☁️ Cloud Deployment (AWS Architecture)

Fashionista-Shop is deployed using **Amazon Web Services (AWS)** to ensure scalability, security, and high availability.

![AWS Architecture](https://github.com/sihamkalach/Fashionista-Shop/blob/main/fashionista-media/aws%20Architecture%20for%20fashionista.png)

### 🔧 AWS Services Used:

- **Amazon S3**: Hosts the frontend (React app) and static assets.
- **Amazon CloudFront**: CDN for fast content delivery and protection via AWS WAF.
- **Amazon EC2**: Runs the Django backend within a secured VPC.
- **Amazon RDS (PostgreSQL)**: Stores all backend data (products, users, orders).
- **Amazon CloudWatch**: Monitoring and logging services.
- **GitHub → EC2**: Deployment from GitHub repo to EC2.
- **Custom Domain**: Managed via Hostinger and connected to CloudFront.

This architecture ensures fast performance, data security, and smooth CI/CD workflows for a seamless online shopping experience.

---

## 📧 Contact

For more information, send me an email: **sihamkalach3@gmail.com**



