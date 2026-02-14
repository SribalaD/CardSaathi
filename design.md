# CardSaathi – System Design Document

“Right Card. Right Benefit. Right Time.”

---

## 1. System Overview

CardSaathi is an AI-powered financial assistant built for Bharat that recommends the best credit/debit card in real time at the moment of payment to maximize cashback, rewards, and benefits.

Unlike traditional solutions that passively list offers, CardSaathi actively recommends the right card based on user identity, spending behavior, and merchant context.

---

## 2. Problem Context

Most Indians miss cashback and reward benefits because:
- They don’t know which card to use.
- They forget category-specific offers.
- They are unaware of hidden benefits.
- Existing apps only show transactions, not optimization.

CardSaathi solves this using AI-driven real-time recommendation.

---

## 3. High-Level Architecture

User (Mobile App / Browser Extension)
        ↓
Smart Frontend (React / Flutter)
        ↓
Secure REST API
        ↓
AI-Powered Backend (Python)
        ↓
Machine Learning Engine
        ↓
Cloud Database (AWS)

---

## 4. Core System Components

### 4.1 Smart Frontend
- Mobile App / Browser Extension
- Real-time checkout detection
- Multilingual interface (Built for Bharat)
- Secure login authentication

---

### 4.2 AI-Powered Backend
- Python-based backend services
- Secure REST API communication
- Context-aware processing
- Merchant & category detection

---

### 4.3 AI Recommendation Engine (Core Innovation)

CardSaathi uses multiple AI techniques:

#### 1. Supervised Machine Learning
- Predicts best card using historical transactions.
- Trained on masked transaction datasets.

#### 2. Unsupervised Learning
- Segments users into:
  - Students
  - Travellers
  - Shoppers
  - Professionals

#### 3. Reinforcement Learning
- Learns from user actions.
- Improves recommendation accuracy over time.

#### 4. AI Ranking Algorithm
- Compares all available cards.
- Calculates expected reward per transaction.
- Ranks cards based on maximum benefit.

---

## 5. AI Data Pipeline

### Datasets Used:
- Masked Transaction Dataset
- Live Card Benefits Dataset
- Merchant & Category Dataset
- User Interaction Dataset

### Processing Steps:
1. Collect user transaction data (masked).
2. Identify spending patterns.
3. Classify user profile.
4. Match merchant category.
5. Rank cards.
6. Recommend best option in real time.

---

## 6. Core Capabilities

- Real-Time Benefit Activation
- Hidden Benefit Discovery
- Usage-Based Card Upgrade Advisor
- Multilingual AI Chatbot
- Transaction Insights
- India-First Card Support (RuPay, Indian Banks)

---

## 7. Cloud & Scalability Design

- AWS Cloud Infrastructure
- Serverless AI Functions
- Cloud-based Databases
- Low-latency real-time recommendation
- Scalable microservices architecture

---

## 8. Security & Privacy Architecture

Security is non-negotiable.

- Card Data Masking (only last 4 digits)
- End-to-End Encryption
- Read-Only Architecture (no payment access)
- Secure authentication system
- Privacy-safe ML training data

---

## 9. Differentiation from Existing Solutions

Existing Apps:
- Passively show offers
- No real-time optimization
- No intelligent profiling

CardSaathi:
- Detects checkout moment
- Context-aware AI
- Personalized benefit maximization
- Learns continuously
- Built specifically for Indian ecosystem

---

## 10. Future Enhancements

- Deep Learning Personalization
- Credit Score Advisory
- Full Bank API Integration
- AI-powered Financial Chatbot
- Predictive Spending Analytics

---

## 11. Impact

- Maximizes value from existing cards
- Reduces financial confusion
- Encourages smarter spending
- Democratizes financial intelligence for Bharat

“Turning every swipe into savings.”