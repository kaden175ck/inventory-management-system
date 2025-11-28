# Inventory Management System | Next.js + Stack Auth

A full-stack **inventory management system** built with **Next.js App Router**, **Stack Auth**, **Prisma**, and **PostgreSQL**.  
It provides authentication, dashboard analytics, product CRUD, and basic inventory monitoring for small businesses or internal tools.

---

## 📋 Table of Contents

1. [Overview](#-overview)
2. [Tech Stack](#-tech-stack)
3. [Features](#-features)
4. [Getting Started](#-getting-started)

---

## 🚀 Overview

This project is a simple but complete **inventory management web app**:

- Users can sign up and log in
- Create, update, and delete products
- Track stock levels and inventory value
- View basic analytics in a dashboard

---

## ⚙️ Tech Stack

- **Next.js (App Router)** – React framework for server components & routing
- **React** – Component-based UI
- **TypeScript** – Type safety and better DX
- **Tailwind CSS** – Utility-first styling
- **Stack Auth** – Authentication & authorization
- **Prisma** – Type-safe ORM and migrations
- **PostgreSQL** – Relational database
- **Recharts** – Charts & visualizations
- **Lucide Icons** – Icon set for UI
- **Vercel** – Hosting & deployment

---

## ⚡️ Features

- 🔐 **Authentication**

  - Email/password auth with Stack Auth
  - Protected routes for authenticated users

- 📦 **Inventory Management**

  - Create, read, update, delete (CRUD) products
  - Fields like name, SKU, price, quantity, category, etc.

- 📊 **Dashboard Analytics**

  - Total number of products
  - Total inventory value
  - Low stock indicators
  - Basic charts for trends (using Recharts)

- 🔍 **Search & Filter**

  - Search products by name / SKU
  - Filter by category (if configured)

- 📄 **Pagination**

  - Paginated product list for large inventories

- ⚠️ **Low Stock Alerts**

  - Highlight items below a configurable quantity threshold

- 📱 **Responsive UI**
  - Layout optimized for desktop and mobile
  - Built with Tailwind CSS

---

## 🧩 Getting Started

### 1. Prerequisites

- [Node.js](https://nodejs.org/) (v18+ recommended)
- [Git](https://git-scm.com/)
- A running **PostgreSQL** instance
  - Local PostgreSQL, or a hosted provider like Neon / Supabase

### 2. Clone & Install

```bash
git clone https://github.com/<your-username>/<your-repo-name>.git
cd <your-repo-name>

npm install
# or
yarn install
# or
pnpm install
# or
bun install
```
