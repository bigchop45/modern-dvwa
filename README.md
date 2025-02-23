# Modern DVWA (Damn Vulnerable Web App)

## 🚀 Overview
This is a **modernized DVWA** (Damn Vulnerable Web Application) built with **React, Django, and FastAPI**. It is an **intentionally vulnerable web application** designed for practicing security testing, ethical hacking, and learning **OWASP Top 10 vulnerabilities**.

### ⚠️ **Disclaimer**
This project is for **educational purposes only**. Do not deploy this on **public servers** or use it for unauthorized penetration testing.

---

## 🔹 Tech Stack
| Component  | Technology |
|------------|------------|
| **Frontend**  | React.js (Next.js) + Tailwind CSS  |
| **Backend**  | Django + Django REST Framework  |
| **API**  | FastAPI (for additional vulnerabilities)  |
| **Database**  | PostgreSQL (intentionally misconfigured)  |
| **Deployment**  | Docker + Kubernetes  |

---

## 📜 Features & Vulnerabilities
✅ **SQL Injection** (Unsanitized database queries in Django API)  
✅ **Cross-Site Scripting (XSS)** (Reflected XSS via FastAPI)  
✅ **Insecure Authentication** (JWT stored in localStorage)  
✅ **Weak Password Storage** (Plaintext passwords)  
✅ **CSRF Vulnerabilities** (Forms lack CSRF protection)  
✅ **Misconfigured PostgreSQL** (Exposed credentials, no SSL)  
✅ **Unvalidated Input** (Lack of input sanitization)  

---

## 📂 Project Structure
```
modern-dvwa/
│── backend/            # Django + FastAPI vulnerable APIs
│   ├── dvwa_backend/   # Django backend
│   ├── api.py         # FastAPI vulnerable routes
│   ├── Dockerfile     # Docker container for backend
│
│── frontend/           # React (Next.js) vulnerable frontend
│   ├── pages/
│   ├── components/
│   ├── Dockerfile     # Docker container for frontend
│
│── docker-compose.yml  # Multi-container setup
│── README.md           # Documentation
```

---

## 🚀 Future Improvements
✅ Add more vulnerabilities (Broken Access Control, SSRF)  
✅ Deploy on AWS/GCP for cloud security testing  
✅ Add secure version for direct comparison  

---

## 📌 Disclaimer
This project is **NOT** for illegal hacking activities. Use only in authorized environments.
