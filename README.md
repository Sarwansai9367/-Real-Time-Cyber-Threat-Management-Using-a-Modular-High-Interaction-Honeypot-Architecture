# 🏥 HealthGov — Secure Healthcare Management Platform

A zero-trust, enterprise-grade healthcare system designed to securely manage patient data, appointments, and medical records with advanced cybersecurity protections.

---

## 📖 Overview

HealthGov is a full-stack healthcare management platform built with a strong focus on security, scalability, and real-time threat detection.

It provides:
- Patient registration and medical record management
- Appointment scheduling and vaccination tracking
- Administrative dashboards and analytics
- Advanced multi-layered security system

The platform follows a **zero-trust architecture**, ensuring all requests are continuously verified and monitored.

---

## 🚀 Features

### 👨‍⚕️ Patient Features
- Patient registration and profile management  
- Medical records (create, view, update)  
- Appointment scheduling  
- Vaccination tracking  
- Prescription management  

### 🛠️ Admin Features
- User management (roles, permissions)  
- Analytics dashboard  
- Health updates CMS  
- Active session monitoring  

### 🔐 Security Highlights
- JWT + Refresh Token Authentication  
- Two-Factor Authentication (TOTP)  
- Rate limiting & brute-force protection  
- Bot detection (fingerprinting + behavior analysis)  
- Honeypot-based attack detection  
- AES-256 encryption for sensitive data  

---

## 🛠️ Tech Stack

| Category | Technology |
|----------|-----------|
| Framework | Next.js 15 |
| Language | TypeScript |
| Database | MongoDB Atlas |
| Authentication | JWT + TOTP |
| Encryption | AES-256, HMAC-SHA256 |
| UI | React, Tailwind CSS |
| Validation | Zod |

---

## 🚀 Getting Started

### Prerequisites
- Node.js 18+
- npm or pnpm
- MongoDB Atlas (or local MongoDB)

### Installation

```bash
# Clone repository
git clone <repository-url>
cd project

# Install dependencies
npm install

# Setup environment variables
cp .env.example .env.local

# Run development server
npm run dev
