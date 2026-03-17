# 🚀 GigShield AI

### AI-Powered Parametric Income Protection for Food Delivery Workers

---

## Disclaimer: 
#### All data, including numbers, locations, and scenarios used in this project, are simulated and provided only for demonstration and prototyping purposes. They are not intended to reflect real-world accuracy.


## 🌟 Overview

GigShield AI is a **real-time, AI-driven insurance platform** designed to protect food delivery workers (Swiggy, Zomato) from **income loss caused by external disruptions**.

Instead of traditional insurance:

* ❌ No manual claims
* ❌ No delays
* ❌ No fixed pricing

👉 We provide:

* ✅ Dynamic weekly pricing
* ✅ Automated claim triggering
* ✅ Instant payouts

---

## ❗ Problem

Delivery workers depend on **daily earnings**, but their income is disrupted by:

* 🌧 Heavy rain & floods
* 🔥 Extreme heat
* 🌫 Pollution spikes
* 🚫 Curfews & protests
* 🚧 Road closures
* 📱 App/server outages

These are:

* Uncontrollable
* Frequent
* Location-specific

👉 Yet, **no system exists to compensate them instantly**

---

## 💡 Solution

GigShield AI introduces a **parametric insurance model**:

> If a real-world disruption occurs → system detects it → payout is triggered automatically

---

## 👤 Target Users

Urban delivery workers in Tier-1 & Tier-2 cities:

* Depend on daily income
* Work in dynamic outdoor conditions
* Face unpredictable disruptions

---

## 🌍 Key Insight: Location-Based Risk

Risk varies by location:

| City      | Risk Type    |
| --------- | ------------ |
| Mumbai    | Rain & Flood |
| Delhi     | Pollution    |
| Hyderabad | Heat         |

👉 Our system uses **location-aware AI pricing**

---

# 🔄 How It Works (System Flow)

### 🧾 Step-by-Step Flow

1. **User Registration**

   * Phone OTP login

2. **Identity Verification**

   * Aadhaar-based eKYC (simulated)
   * Privacy-safe hashing

3. **Location Capture**

   * GPS enabled

4. **AI Risk Assessment**

   * Based on location + historical data

5. **Dynamic Weekly Premium**

   * AI calculates next week risk
   * AutoPay renews policy

6. **Real-Time Monitoring**

   * Weather + AQI
   * Maps (traffic/closures)
   * Crowd signals
   * Platform activity

7. **Event Detection (AI)**

   * Multi-source confidence scoring

8. **Fraud Detection**

   * Multi-layer validation

9. **Auto Claim Generation**

   * No manual input

10. **Instant Payout**

* UPI / wallet (mock)

---

## ⚡ One-Line Flow

> Detect → Validate → Trigger → Pay

---

# 🧠 AI Pricing Engine

### 🔹 Key Idea

Premium depends on **probability of disruption**

---

### 📊 Risk Model

Risk is calculated using multiple factors:

[
Risk = Environmental + Social + Platform + Infrastructure + Demand
]

---

### 💰 Premium Model

[
Premium = Base \times (1 + Risk)
]

✔ Dynamic
✔ Weekly updated
✔ Location-aware

---

### ⚖️ Constraints

* ₹10 ≤ Premium ≤ ₹30
* Max weekly change: 20%

---

# 🚨 Fraud Detection System

We implement a **multi-layer fraud engine**:

### 🔍 Checks:

* 📍 Location validation (GPS + spoof detection)
* ⏱ Time validation (active hours)
* 🔁 Duplicate claims
* 📱 Device & identity verification
* 🧠 Behavioral anomaly detection
* 🔬 Micro-fraud detection

---

### 🔐 Identity Protection

* Aadhaar eKYC (simulated)
* Hashed identity (no raw storage)
* One user = one account

---

# ⚙️ Technology Stack

### 📱 Frontend

* Flutter (Mobile App)
* Next.js (Web Dashboard)

---

### ⚙️ Backend

* FastAPI (Python)
* Microservices architecture

---

### 🤖 AI / ML

Scikit-learn (Baseline Models & Prototyping)

XGBoost / LightGBM (High-performance gradient boosting for risk prediction)

PyTorch (Deep learning & temporal models like LSTM)

Pandas / NumPy (Data processing & feature engineering)

⚡ Advanced Capabilities

Time-Series Modeling (LSTM / Prophet) → Forecast disruptions

Anomaly Detection (Isolation Forest, LOF) → Fraud detection

Feature Engineering Pipelines (sklearn pipelines)

Explainable AI (SHAP, feature importance) → Model transparency

Real-Time Inference APIs (FastAPI + model serving)

Online / Incremental Learning → Continuous model updates

🧠 Optional (Next-Level / Bonus)

Graph-based models (network risk propagation)

Federated Learning (privacy-preserving training)

Reinforcement Learning (adaptive pricing strategies)
---

### 🗄 Database

* PostgreSQL
* Redis (real-time cache)

---

### 🌐 APIs

* Weather API
* AQI API
* Google Maps API

---

### 💳 Payments

* Razorpay (test mode)

---

# 🏗 System Architecture

* Microservices-based
* Event-driven (Kafka/queue)
* AI as independent service
* Cloud-native (AWS/Azure)

---

### 🔄 Architecture Flow

```
Mobile/Web App
      ↓
API Gateway
      ↓
Microservices
      ↓
Event Engine + AI Models
      ↓
Fraud Detection
      ↓
Claim Engine
      ↓
Payment Gateway
```

---

# 📦 Core Modules

* Risk Engine
* Pricing Engine
* Monitoring Engine
* Event Detection Engine
* Fraud Detection Engine
* Claims Engine
* Payment Engine
* Dashboard Engine

---

# 📊 Features

### 👤 User

* Weekly subscription
* AutoPay
* Real-time alerts
* Earnings protection dashboard

---

### 🧑‍💼 Admin

* Risk heatmaps
* Fraud monitoring
* Claim analytics
* Predictive insights

---

# 🚀 Optional Advanced Features

* 🗺 Live risk heatmaps
* 📊 Explainable AI (why premium changed)
* 🔔 Smart notifications
* 📉 Demand prediction
* 🤝 Platform API integration (future)

---

# 🧪 MVP Scope

* Registration
* Risk calculation
* Weekly premium
* Trigger simulation
* Auto claim
* Mock payout

---

# 📅 Implementation Plan

### Week 1–2

* Design + README

### Week 3–4

* Backend + AI + APIs

### Week 5–6

* Fraud + AutoPay + dashboard

---

# 🧠 Key Innovation

* Multi-source disruption detection
* AI-based dynamic pricing
* Zero-touch claims
* Micro-level fraud prevention
* Subscription-based insurance

---

# 🎯 Final Summary

> GigShield AI transforms insurance into a real-time, intelligent system that automatically protects gig workers’ income using AI, data, and automation.

---

# 🔥 Impact

* Financial security for gig workers
* Scalable across gig economy
* Bridges gap between insurance and real-time data

---
