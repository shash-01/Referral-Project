# ReferralHub – AI-Powered Referral Management Platform

## 🚀 Overview

ReferralHub is a full-stack AI-powered professional networking and referral management platform designed to connect job seekers with employees willing to provide referrals. The platform enables users to create professional profiles, upload resumes, discover professionals through advanced search filters, post referral opportunities, apply for referrals, track application status, and receive notifications throughout the referral process.

The project aims to simplify and automate the referral ecosystem by combining modern web technologies with machine learning-driven recommendations and candidate ranking.

---

## ✨ Key Features

### 🔐 Authentication & Security

* User Registration & Login
* JWT-Based Authentication
* Secure Password Hashing using BCrypt
* Protected API Routes
* Role-Based Access Control (Future)

### 👤 Professional User Profiles

* LinkedIn-Style Public Profiles
* Unique Username Support
* Profile Picture Upload
* Resume Upload & Management
* Bio Section
* Skills Management
* Work Experience Tracking
* Education Details
* GitHub & LinkedIn Profile Links

### 🔍 User Discovery & Search

Users can search professionals based on:

* Name
* Username
* Company
* Job Role
* Skills

This helps job seekers find employees working in their target companies and request referrals.

### 🤝 Referral Management

* Create Referral Requests
* Track Referral Status
* Pending / Accepted / Rejected States
* Manage Referral History

### 📢 Referral Marketplace

Employees can:

* Create Referral Opportunities
* Add Company & Job Details
* Publish Referral Posts
* Manage Applicants

Job Seekers can:

* Browse Referral Opportunities
* Apply Directly to Referral Posts
* Track Application Progress

### 📄 Resume Management

* Resume Upload using Multer
* Cloudinary Integration
* Secure Cloud Storage
* Resume Access for Referrers

### 🔔 Notification System

* Application Notifications
* Referral Acceptance Notifications
* Referral Rejection Notifications
* Mark Notifications as Read
* Delete Notifications

### 📊 Dashboard & Analytics (Planned)

* Total Applications
* Accepted Applications
* Rejected Applications
* Pending Applications
* Referral Statistics
* User Activity Insights

---

## 🤖 AI & Machine Learning Features

ReferralHub incorporates Machine Learning to improve referral matching and candidate discovery.

### Smart Referral Matching

The platform analyzes:

* Skills
* Experience
* Education
* Job Preferences
* Company Preferences

to recommend relevant referral opportunities.

### Candidate Ranking System

Applicants can be ranked based on:

* Skill Match Percentage
* Experience Relevance
* Resume Quality
* Profile Completeness

### Resume Analysis

The system can extract:

* Skills
* Education
* Experience
* Certifications

from uploaded resumes to enrich user profiles automatically.

### Recommendation Engine

The platform can suggest:

* Relevant Referral Opportunities
* Potential Referrers
* Similar Professionals
* Recommended Companies

### Future AI Enhancements

* ATS Resume Scoring
* Resume Parsing using NLP
* Referral Success Prediction
* Job Recommendation System
* LLM-Based Career Assistant
* Semantic Search using Vector Embeddings

---

## 🛠️ Technology Stack

### Frontend

* React.js
* Tailwind CSS
* Axios
* React Router

### Backend

* Node.js
* Express.js

### Database

* MongoDB
* Mongoose

### Authentication

* JWT
* BCryptJS

### File Upload & Storage

* Multer
* Cloudinary

### Machine Learning

* Python
* Scikit-Learn
* Pandas
* NumPy
* FastAPI
* FAISS
* Sentence Transformers

### DevOps & Scalability (Planned)

* Docker
* Docker Compose
* Redis
* RabbitMQ
* Kubernetes
* API Gateway

---

## 📂 Project Architecture

```text
Frontend (React.js)
        │
        ▼
REST APIs (Express.js)
        │
        ▼
MongoDB Database
        │
        ├── User Profiles
        ├── Referrals
        ├── Applications
        └── Notifications
        │
        ▼
Cloudinary Storage
        │
        ├── Resumes
        └── Profile Pictures

Future:
ML Recommendation Service (Python/FastAPI)
Redis Cache
RabbitMQ Event Bus
Dockerized Microservices
```

---

## 📌 Core Modules

### User Module

* Registration & Login
* Profile Management
* Resume Upload
* Profile Picture Upload
* Public Profiles
* Search Users

### Referral Module

* Create Referral Requests
* Manage Referral Status
* Track Referrals

### Referral Marketplace Module

* Create Referral Posts
* Browse Referral Opportunities
* Filter Referral Posts

### Application Module

* Apply to Referral Posts
* View Applications
* Accept / Reject Applications
* Manage Applicants

### Notification Module

* View Notifications
* Mark as Read
* Delete Notifications

### AI Recommendation Module (Planned)

* Smart Referral Matching
* Candidate Ranking
* Resume Analysis
* Job Recommendations

---

## 🎯 Future Roadmap

### Professional Networking

* Follow / Unfollow Users
* Connection Requests
* Professional Network Graph

### Communication

* Direct Messaging
* Real-Time Chat
* Referral Discussion Threads

### AI Features

* Resume Scoring
* AI Career Assistant
* Personalized Recommendations
* Candidate Ranking System

### Scalability

* Redis Caching
* RabbitMQ Event Processing
* Docker Deployment
* Kubernetes Orchestration
* Microservices Architecture

---

## 📚 Learning Outcomes

This project demonstrates:

* Full-Stack Web Development
* REST API Design
* Authentication & Authorization
* Cloud Storage Integration
* MongoDB Data Modeling
* Search & Filtering Systems
* Notification Systems
* Professional Networking Platform Design
* Machine Learning Integration
* Scalable Software Architecture

---

## 👨‍💻 Author

Shashank Mishra

MCA, VIT Vellore

Tech Stack: Java, JavaScript, React.js, Node.js, Express.js, MongoDB, Python, Scikit-Learn, Cloudinary
