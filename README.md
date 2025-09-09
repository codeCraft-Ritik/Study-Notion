# 📚 StudyNotion - EdTech Platform

![MERN](https://img.shields.io/badge/Stack-MERN-blueviolet?style=flat-square)
![Contributions](https://img.shields.io/badge/Contributions-Welcome-brightgreen?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-orange?style=flat-square)

StudyNotion is a **full-featured EdTech platform** built with the **MERN stack** that empowers students to learn interactively 📖, instructors to share knowledge 👨‍🏫, and admins to manage the ecosystem ⚙️.

---

## 📑 Table of Contents

- [Introduction](#-introduction)
- [System Architecture](#-system-architecture)
- [Features](#-features)
- [API Design](#-api-design)
- [Installation](#-installation)
- [Configuration](#-configuration)
- [Usage](#-usage)
- [Preview](#-preview)
- [Dependencies](#-dependencies)
- [Folder Structure](#-folder-structure)
- [Contributing](#-contributing)
- [Contact](#-contact)

---

## 🚀 Introduction

**StudyNotion** aims to provide a **seamless, engaging, and scalable** learning experience.  
It serves **students** with interactive courses, **instructors** with a platform to monetize expertise, and eventually **admins** with control over the platform.  

---

## 🏗 System Architecture

The project follows a **client-server architecture** with three main components:

### 🎨 Frontend (React + TailwindCSS)
- **For Students**: Homepage, Course List, Wishlist, Checkout, Course Content, User Profile  
- **For Instructors**: Dashboard, Insights, Course Management, Profile Management  
- **For Admins (Future Scope)**: Platform Dashboard, User & Instructor Management, Insights  

### ⚙️ Backend (Node + Express)
- Authentication & Authorization (JWT + OTP + Reset Password)  
- Course Management (CRUD for instructors)  
- Student Course Purchase (Razorpay integration)  
- Cloud-based Media Management (Cloudinary)  
- Markdown Support for content  

### 🗄 Database (MongoDB)
- User Data  
- Courses & Content  
- Orders & Payments  

---

## ✨ Features

✅ Student & Instructor Authentication  
✅ Course Management & Rating System  
✅ Wishlist & Cart Checkout  
✅ Payment Gateway Integration (Razorpay)  
✅ Media Storage with Cloudinary  
✅ Insights & Analytics (Instructor + Admin)  
✅ Secure Password Reset (Email OTP)  

---

## 📡 API Design

- Follows **REST Architecture**  
- Built with **Express.js**  
- Data Format: **JSON**  
- Methods: `GET, POST, PUT, DELETE`  

---

## 📸 You can preview the StudyNotion platform

<img width="1905" height="917" alt="Image" src="https://github.com/user-attachments/assets/38aa9e9a-95f3-4779-a414-825cc5cf5658" /> 

<img width="1919" height="916" alt="Image" src="https://github.com/user-attachments/assets/3123efeb-4bf2-4dff-a076-e14ad4404037" />

<img width="1909" height="905" alt="Image" src="https://github.com/user-attachments/assets/74568607-e17d-49f0-bd37-6d7ca95fb9a8" />

<img width="1910" height="903" alt="Image" src="https://github.com/user-attachments/assets/bb95542a-2312-4272-a48a-3f661da74017" />

<img width="1919" height="909" alt="Image" src="https://github.com/user-attachments/assets/bd10c137-4c7e-4e4a-98f7-9bdd38e2e71d" />

<img width="1919" height="907" alt="Image" src="https://github.com/user-attachments/assets/eb5bbbc1-f9b5-4e14-8759-2cc92584dd46" />

<img width="1919" height="905" alt="Image" src="https://github.com/user-attachments/assets/4bec4ea7-1c2e-4e67-9034-721390f5e19b" />



---

## ⚡ Installation

Clone the repository and install dependencies:

```bash
# Clone repo
git clone https://github.com/codeCraft-Ritik/Study-Notion---EdTech-Platform.git
cd StudyNotion

# Install backend
cd Server && npm install

# Install frontend
cd .. && npm install
