# 🚀 BrandPulse Intelligence Dashboard

A serverless real-time sentiment analysis system built using AWS to monitor customer feedback and detect negative sentiment instantly.

---

## 📌 Overview

BrandPulse is a cloud-based dashboard that analyzes user input (reviews, comments, feedback) and classifies sentiment as Positive, Negative, or Neutral.  
It also triggers real-time alerts when negative sentiment is detected.

---

## 🎯 Key Features

- 🔍 Real-time Sentiment Analysis  
- 🚨 Automatic Email Alerts (SNS)  
- 🗄️ Data Storage using DynamoDB  
- ⚡ Serverless Architecture  
- 🌐 Cloud-based Deployment (S3 + CloudFront)  
- 🔐 Secure Authentication (Cognito)  

---

## 🏗️ Architecture

User → Cognito → CloudFront → S3 → API Gateway → Lambda → DynamoDB  
                                                             ↓  
                                                            SNS  

---

## 🧠 How It Works

1. User enters feedback in the dashboard  
2. Request is sent to API Gateway  
3. Lambda function processes sentiment  
4. Result is stored in DynamoDB  
5. SNS sends alert if sentiment is negative  
6. Response is displayed on UI  

---

## 🛠️ Tech Stack

- Frontend: HTML, CSS, JavaScript  
- Backend: AWS Lambda (Python)  
- API: Amazon API Gateway  
- Database: Amazon DynamoDB  
- Alerts: Amazon SNS  
- Hosting: Amazon S3 + CloudFront  
- Authentication: Amazon Cognito  

---

## 📊 Use Cases

- 📣 Brand Monitoring  
- 🚨 Crisis Detection  
- 💬 Customer Feedback Analysis  

---

## ⚠️ Limitations

- Rule-based sentiment analysis (not AI/ML-based)  
- No direct social media API integration  
- URL-based analysis is simulated  

---

## 🔮 Future Improvements

- Integrate Amazon Comprehend for AI-based analysis  
- Add real-time social media data (Twitter API)  
- Improve sentiment accuracy using ML models  
- Advanced analytics dashboard  

---

## 📷 Preview

ss.png

---

## 👨‍💻 Author

Surya T

---

## 📄 License

This project is for academic and demonstration purp
