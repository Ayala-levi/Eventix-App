# Eventix-App  
A full TypeScript (React + Express) monorepo using Supabase and deployed on Render and Cloudflare. Built during a Full Stack internship in web development for coordinating family meals, Shabbat plans, and events.

## 🍽️ About Eventix

An interactive bilingual system for organizing communal meals, Shabbat planning, and event coordination – with quick WhatsApp sharing and robust admin tools.

---

## 🧩 General Overview

Eventix is a community-oriented platform for managing family and communal life, including:

- 📅 **Events** – Create and manage group events (including meal assignments)  
- 🧑‍🍳 **Meal Trains** – Coordinate meals for families in need (e.g. after birth, military duty)  
- 🕯️ **Shabbat Sync** – Plan Shabbat and holidays (who's going where and when)  
- 📊 **Analytics** – An admin dashboard with useful usage metrics  

---

## 🌐 Main Technologies

| Domain       | Technologies                          |
|--------------|----------------------------------------|
| Frontend     | React, TypeScript, Tailwind CSS, MUI, i18next |
| Backend      | Node.js, Express, TypeScript           |
| Database     | Supabase (PostgreSQL) with RLS         |
| Auth         | Google Sign-In, JWT                    |
| Realtime     | Socket.io                              |
| API          | REST API + Axios                       |
| Deployment   | Cloudflare (Frontend), Render (Backend) |
| Storage      | Supabase Storage + Multer              |
| Dev Tools    | VS Code, Postman, ClickUp, GitHub      |

---

## 👩‍💻 Responsibilities & Personal Contribution

- 🔐 Google Sign-In integration + JWT handling  
- 🧾 Endpoint to fetch connected user via token  
- 🧑‍🍳 User table setup + dietary preferences structure  
- 🛡️ Admin permissions (user management, meal deletion, view all Shabbat/events)  
- 🌐 Responsive navigation with translation, profile image, and permission-based UI  
- 📊 Built an analytics dashboard with graphs for Events, Meals, and ShabbatSync  
- 📈 Implemented Weekly Active Accounts metric  
- 🚀 Production deployment (Render, Cloudflare, Supabase, env variables)  
📚 [Project Book – Full Documentation & My Development Tasks](https://drive.google.com/file/d/1YFo6P_7ktjlZ3goXneQjOl8YpzOeoJNi/view?usp=sharing)  
Includes project goals, client and company background, system description, work process, and a detailed breakdown of the features and development tasks I personally implemented.
---

## 🔐 Admin Permissions

| Module         | Special Permissions                                    |
|----------------|--------------------------------------------------------|
| Users          | View, search, edit, delete                             |
| Events         | Full access to all events, edit, remove participants, manage dietary restrictions |
| Meal Trains    | Edit any schedule, filter and delete                   |
| Shabbat Plans  | View all plans, delete if needed                       |
| Analytics      | Full access to usage reports and graphical statistics  |

---

## 🚀 Deployment & Domains

| Component      | URL                                            |
|----------------|-------------------------------------------------|
| Frontend       | https://eventix-770.pages.dev/                  |
| Backend        | https://eventix-backend-hiii.onrender.com       |
| Database       | Supabase (managed, secured with RLS)            |

---

## 🧪 Testing & Operation

- Manual testing on frontend and backend (Desktop + Mobile)  
- API testing with Postman (including auth and tokens)  
- Permission testing by role (Admin, Regular User, Guest)  
- Analytics monitoring and live usage graphs  

---

## 🎯 System Purpose

To help families and communities coordinate Shabbat, holidays, meals, and events – in a simple, collaborative, and accessible way.

---

## 📄 Additional Info

- Developed as part of a 2025 internship  
- Built by a team of developers, managers, and designers  
- Agile workflow with task management in ClickUp  

---

## 👏 Special Thanks

Special thanks to Avigail, CEO of Diversitech, to Michal the team lead, and to the team members for their professional guidance, ongoing support, and collaboration throughout all stages of development.
