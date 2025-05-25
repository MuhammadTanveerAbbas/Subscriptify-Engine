<div align="center">
  <img src="https://i.postimg.cc/jqc8NgQ8/image.png" alt="Subscriptify Engine Logo" />
</div>

<h1 align="center">🚀 Subscriptify Engine</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Node.js-339933?logo=nodedotjs&logoColor=white&style=for-the-badge" alt="Node.js" height="40" />
  <img src="https://img.shields.io/badge/Express-000000?logo=express&logoColor=white&style=for-the-badge" alt="Express" height="40" />
  <img src="https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white&style=for-the-badge" alt="MongoDB" height="40" />
</p>

---

## 📦 Features

- 🔐 **Secure Authentication** — JWT-based login with role-based access  
- 📊 **Subscription Management** — Full CRUD for tracking and managing subscriptions  
- 🧠 **Smart Rate Limiting** — Arcjet API integration for security and bot mitigation  
- ⚙️ **Automated Workflows** — Email reminders and background tasks via Upstash QStash  
- 🧱 **Production-Ready Stack** — Robust error handling, schema validation, and logging  
- 📬 **Email Integration** — Nodemailer-driven transactional emails with templating  

---

## 🛠 Tech Stack

### Version Prerequisites

- **Node.js**: 18.x  
- **Express**: 4.x  
- **MongoDB**: 6.x  

### Security Stack

- JWT for secure authentication  
- Arcjet for intelligent rate limiting  
- Helmet & CORS for HTTP security headers  

### Services Used

- **Upstash QStash** for scheduled workflows  
- **Nodemailer** for email delivery  

---

## ⚡ Quick Start

### Prerequisites

- Node.js 18+  
- MongoDB instance (local or cloud)  
- Upstash account (for QStash)  

### Setup

```bash
# Clone repository
git clone https://github.com/MuhammadTanveerAbbas/Subscriptify-Engine.git
cd Subscriptify-Engine

# Install dependencies
npm install

# Configure environment variables
cp .env.example .env.local
nano .env.local

# Start development server
npm run dev
