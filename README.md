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

<img width="1909" height="912" alt="Image" src="https://github.com/user-attachments/assets/c919a11b-e99b-49d3-8bc6-dc3639a58779" />

<img width="1913" height="907" alt="Image" src="https://github.com/user-attachments/assets/8343c999-f300-4a77-9756-ecf53a02c820" />

<img width="1910" height="909" alt="Image" src="https://github.com/user-attachments/assets/0c87d121-8ed3-4f65-8ca0-f3be4eb329c3" />

<img width="1908" height="907" alt="Image" src="https://github.com/user-attachments/assets/6729d142-902b-407a-8ac7-142a51faa966" />

<img width="1907" height="834" alt="Image" src="https://github.com/user-attachments/assets/aee1dda6-f239-4603-b986-9105292ae296" />

<img width="1916" height="903" alt="Image" src="https://github.com/user-attachments/assets/c22a3e9e-fb40-40a1-82fa-463e44dee0a6" />

<img width="1915" height="908" alt="Image" src="https://github.com/user-attachments/assets/243795e6-b706-4b16-8d44-37995fdb5c6a" />

<img width="1915" height="903" alt="Image" src="https://github.com/user-attachments/assets/32fb9004-f77f-479b-a743-64dd215d15b2" />



---

## ⚡ Installation

Clone the repository and install dependencies:

```bash
# Clone repo
git clone https://github.com/codeCraft-Ritik/Study-Notion.git
cd StudyNotion

# Install backend
cd Server && npm install

# Install frontend
cd .. && npm install
