# 🌾🚀 Fasal360  
### 🧠 AI-Powered Agri Intelligence Super App  
> Smart Farming • Smart Decisions • Smart Future  

---

<div align="center">

![Status](https://img.shields.io/badge/Status-Active-success?style=for-the-badge)
![Backend](https://img.shields.io/badge/Backend-Flask-blue?style=for-the-badge)
![Database](https://img.shields.io/badge/Database-PostgreSQL-336791?style=for-the-badge)
![AI](https://img.shields.io/badge/AI-ML%20Models-orange?style=for-the-badge)
![Frontend](https://img.shields.io/badge/Frontend-Bootstrap%20%7C%20ChartJS-purple?style=for-the-badge)

</div>

---

# 📘 Software Requirements Specification (SRS)

---

# 🌟 1. Introduction

## 🎯 1.1 Purpose
Fasal360 is an AI-powered agricultural decision-support platform designed to empower farmers with intelligent, data-driven insights to increase productivity, profitability, and sustainability.

---

## 🌍 1.2 Scope

Fasal360 includes **12 AI-powered agricultural modules** covering:

- 🌱 Crop Management  
- 🐄 Livestock Intelligence  
- 📦 Supply Chain Risk Analysis  
- 🌿 Sustainable Farming  
- 🏛 Government Scheme Tracking  
- 🤖 AI Farmer Advisory  

✨ Supports:
- English & Hindi (Multilingual)
- Real-time Predictions
- Interactive Dashboards
- AI-based Reporting

---

# 🏗 2. Overall Description

## 🔭 2.1 Product Perspective

Fasal360 is a **Web-Based Intelligent Agriculture Platform**

### 🧩 Technology Stack

| Layer | Technology |
|-------|------------|
| Backend | Flask |
| Database | PostgreSQL |
| AI/ML | Scikit-learn, YOLOv8 |
| Frontend | HTML5, Bootstrap, Chart.js |
| Architecture | MVC-inspired |

---

## 🎯 2.2 Product Goals

- ✔ Increase farmer income through AI insights  
- ✔ Reduce crop losses via early disease detection  
- ✔ Improve access to government schemes  
- ✔ Promote sustainable agriculture  
- ✔ Provide simple rural-friendly digital tools  

---

# ⚙ 3. Functional Requirements

---

## 👤 3.1 User Management

### 📝 Registration
Users must register using:
- Name  
- Email / Mobile  
- Password  

🔐 Passwords must be encrypted (bcrypt).

---

### 🔐 Login
- Secure credential verification  
- Session management implementation  

---

### 🧑‍🌾 Farmer Profile
The system shall allow farmers to store:

- Soil type  
- Land size  
- Location  
- Crop focus  
- Livestock details  
- Farm history  

---

### 📊 Prediction History
- All AI predictions shall be logged  
- Users can view historical insights  

---

# 🤖 4. AI Module Functional Requirements

---

## 🌾 4.1 Crop Recommendation
**Input:** N, P, K, pH, temperature, humidity, rainfall  
**Output:** Recommended crop  
**Model:** Random Forest Classifier  

---

## 🍂 4.2 Disease Detection
**Input:** Leaf image  
**Output:** Disease classification + confidence score  
**Model:** YOLOv8  
⏱ Inference Time ≤ 5 seconds  

---

## 📈 4.3 Yield & Profit Prediction
**Input:** Crop type, land area, input cost  

**Output:**
- Predicted yield (tons/hectare)  
- Estimated profit  

**Model:** Linear Regression  

---

## 🐄 4.4 Livestock Breed Recognition
**Input:** Animal image  
**Output:** Breed classification  
**Model:** CNN / YOLOv8  

---

## 💬 4.5 Farmer Chatbot
**Input:** Text query (Hindi / English)  
**Output:** Relevant advisory response  
**Method:** TF-IDF + Cosine Similarity  

---

## 🚛 4.6 Supply Chain Risk Analysis
**Input:**  
- Distance  
- Transit time  
- Storage condition  

**Output:**  
- Risk Score  
- Advisory Recommendation  

---

## 🌿 4.7 Eco-Farming Score
**Input:**  
- Organic usage  
- Water efficiency  
- Fertilizer usage  

**Output:**  
- Sustainability score  
- Reward level  

---

## 🧅 4.8 Onion Storage Prediction
**Input:** Humidity, Temperature, Storage Days  
**Output:** Spoilage Risk (%)  

---

# 🏛 5. Personalized Government Services

System shall display:

- PM Fasal Bima Yojana Status  
- PM Kisan Samman Nidhi Status  
- Subsidy Approval Status  
- Loan Application Status  
- Eligible Schemes  
- Masked Bank Details  

---

# 🖥 6. Interface Requirements

---

## 📱 6.1 Responsive Design
Must support:
- Mobile  
- Tablet  
- Desktop  

---

## 🧭 6.2 Dashboard
- Central hub for 12 modules  
- Icon-based navigation  
- Section-based scrolling  

---

## 📊 6.3 Data Visualization
- Chart.js integration  
- Yield trends  
- Profit projections  
- Sustainability graphs  

---

## 🌐 6.4 Multilingual Support
- English  
- Hindi  
- Toggle-based switching  

---

# 🔒 7. Non-Functional Requirements

---

## ⚡ Performance
- Image Prediction ≤ 5 sec  
- Page Load ≤ 3 sec  

---

## 🛡 Security
- bcrypt password hashing  
- Input validation  
- SQL injection prevention  
- HTTPS enforcement  

---

## 📈 Scalability
- Modular AI engines  
- REST API compatible  
- Microservice-ready architecture  

---

## 🔄 Reliability
- Fallback responses if AI fails  
- Error handling & logging  

---

## 👨‍🌾 Usability
- Icon-driven interface  
- Simple farmer-friendly language  
- Rural accessibility focus  

---

# 🔌 8. External Interfaces

---

## 📷 Hardware
- Smartphone camera (image uploads)  
- Desktop browser support  

---

## 🔗 Software (Future Integrations)
- Weather APIs  
- Government Scheme APIs  

---

# 🚀 9. Future Enhancements

- 🛰 Real-time satellite data integration  
- 📱 Mobile App (Flutter / React Native)  
- 🎙 Voice-based farmer assistant  
- ⛓ Blockchain supply chain tracking  
- 🌍 Carbon credit marketplace  

---

# ⚠ 10. Constraints

- Initial release: Monolithic Flask app  
- AI models hosted locally  
- Internet connectivity required  

---

<div align="center">

## 🌱 Fasal360 — Empowering Farmers with AI

</div>
