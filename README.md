# 🍺 Beer Stock Management System

A scalable, secure, and responsive web application built with **.NET Core (Web API)** and **React.js (Tailwind + Vite)** to manage beer stock across multiple hotel locations with advanced role-based access control.

---

## 🌐 Live Preview

> (Add your deployed URL here)

---

## 📦 Tech Stack

| Layer       | Technology                          |
|------------|--------------------------------------|
| Frontend   | React.js, Tailwind CSS, Vite         |
| Backend    | ASP.NET Core Web API (C#)            |
| Auth       | ASP.NET Identity + JWT + OAuth       |
| Database   | SQL Server + Entity Framework Core   |
| Hosting    | Azure App Services / AWS             |
| CI/CD      | GitHub Actions / Azure Pipelines     |

---

## 🚀 Features

### Core Modules
- ✅ Multi-location hotel management
- ✅ Daily beer stock entry & auto tally
- ✅ Inventory tracking per hotel
- ✅ Responsive dashboards for mobile, tablet, desktop

### Admin Tools
- ⚙️ Dynamic UI Builder (add/remove fields, panels, pages)
- 🎨 Theme customization (font, color, layout)
- 🔐 App Lock Scheduler (start/end date)
- 🏷️ Role-permission system with real-time control

### Role-Based Access
| Role        | Access Level                                                 |
|-------------|--------------------------------------------------------------|
| **Admin**   | Full access + settings + customization                       |
| **Developer** | Full access + theme and component configuration              |
| **Tester**  | Full access + UI testing and toggling features                |
| **Supervisor** | Full access + access control per user/hotel               |
| **Owner**   | Multi-location dashboard access                              |
| **Manager** | Hotel-specific dashboard access                              |
| **Staff**   | Basic access to assigned hotel modules                        |

### Optional Features
- 🔔 Notifications (low stock)
- 📱 QR/Barcode scanner for mobile
- 🌍 Multi-language support
- 🌙 Dark/Light Theme
- 📴 Offline-first with sync

---

## 🏗️ Folder Structure

### Backend - `.NET Core API`
