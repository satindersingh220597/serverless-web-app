# 🚀 AWS Serverless Web Application

This project demonstrates a fully serverless web application built using AWS services.

## 🧩 Architecture
- **Frontend**: Amazon S3 (Static Website Hosting)
- **API Layer**: Amazon API Gateway (HTTP API)
- **Backend**: AWS Lambda (Node.js)
- **Security**: CORS enabled

## 📊 Flow Diagram
<img width="1536" height="1024" alt="s3_lambda_apigateway" src="https://github.com/user-attachments/assets/56d0b88d-6e72-456c-b243-f510c072fbc0" />

## 📊 Structure
serverless-web-app/
│
├── frontend/
│   └── index.html
│
├── backend/
│   └── lambda-handler.js
│
├── architecture/
│   └── flowchart.png
│
└── README.md

## 🔄 Application Flow
1. User accesses the static website hosted on S3.
2. User clicks the "Call Backend" button.
3. JavaScript sends an HTTP request to API Gateway.
4. API Gateway invokes an AWS Lambda function.
5. Lambda processes the request and returns a response.
6. The browser updates the UI dynamically.

## 🛠️ Technologies Used
- AWS S3
- AWS Lambda
- API Gateway
- JavaScript
- HTML

## ✅ Features
- Fully serverless architecture
- No backend servers required
- Scalable and cost-effective
- CORS-enabled API integration

## 📌 How to Run
1. Upload `frontend/index.html` to an S3 bucket.
2. Deploy Lambda code in AWS Lambda.
3. Connect Lambda to API Gateway.
4. Enable CORS in API Gateway.
5. Open the S3 static website URL.

## 👤 Author
Satinder Singh
