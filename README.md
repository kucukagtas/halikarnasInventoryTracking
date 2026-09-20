# 📦 Halikarnas Inventory Tracking — E-Commerce Admin & Inventory Management Dashboard

<div align="center">

[![Live Demo](https://img.shields.io/badge/Live_Demo-kucukagtas.github.io%2FhalikarnasInventoryTracking-9d5175?style=for-the-badge&logo=githubpages&logoColor=white)](https://kucukagtas.github.io/halikarnasInventoryTracking/)
[![Language: Turkish](https://img.shields.io/badge/Language-Turkish_%28T%C3%BCrk%C3%A7e%29-E30A17?style=for-the-badge&logo=googletranslate&logoColor=white)](https://kucukagtas.github.io/halikarnasInventoryTracking/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](LICENSE)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![Bootstrap 5](https://img.shields.io/badge/Bootstrap_5.3.3-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)](https://getbootstrap.com/)
[![Font Awesome](https://img.shields.io/badge/Font_Awesome_6.7.2-528DD7?style=for-the-badge&logo=font-awesome&logoColor=white)](https://fontawesome.com/)

<p align="center">
  <strong>A modern, responsive e-commerce admin and inventory management dashboard for Halikarnas Saat — published in Turkish.</strong>
</p>

[🌐 Visit Live Website](https://kucukagtas.github.io/halikarnasInventoryTracking/) • [✨ Key Features](#-key-features) • [🛠️ Tech Stack](#️-tech-stack) • [📁 Project Structure](#-project-structure) • [🚀 Getting Started](#-getting-started) • [🌐 Deployment](#-deployment) • [📄 License](#-license)

---

</div>

## 📖 Overview

**Halikarnas Inventory Tracking** is a comprehensive, multi-page admin and inventory control dashboard designed to manage catalog, order fulfillment, and user operations for the **Halikarnas Saat** luxury e-commerce ecosystem. The application offers store managers and administrators a centralized hub to monitor live financial metrics, track stock levels, manage multi-tier product categories, and streamline customer order workflows.

🇹🇷 **Dil Notu:** Yönetim paneli arayüzü, gezinme menüleri, sipariş takibi, kategori/ürün yönetimi ve hesap formları tamamen **Türkçe** olarak yapılandırılmıştır (*"Halikarnas Admin - Stok ve Envanter Yönetim Paneli"*).

Built with semantic **HTML5**, **Bootstrap 5.3.3**, custom **CSS3**, and **Font Awesome 6.7.2**, the dashboard delivers a cohesive user experience with fluid responsiveness across desktops, laptops, tablets, and mobile screens.

🔗 **Live Deployment:** [https://kucukagtas.github.io/halikarnasInventoryTracking/](https://kucukagtas.github.io/halikarnasInventoryTracking/)

---

## ✨ Key Features

- **📊 Executive Metrics & Dashboard Overview:**
  - High-level KPI summary cards showcasing total sales volume, order counts, active product numbers, and pending inquiries.
  - Recent orders log with live status indicators and instant access to detailed receipts.
  - Tabular financial breakdown categorizing sales metrics by payment methods and product lines.
- **🏷️ Multi-Tier Category Management:**
  - Comprehensive category listings with integrated thumbnail previews, active product counts, and status badges.
  - Dedicated category creation and editing forms supporting fast catalog reorganization.
- **🛍️ Product Catalog & Real-Time Stock Tracking:**
  - Centralized inventory database with SKU images, product names, assigned categories, unit pricing, and stock counters.
  - Visual stock alerts and operational status switches (Active / Inactive).
  - Rich product addition and modification interface featuring image upload previews and pricing controls.
- **🖼️ Storefront Slider & Showcase Control:**
  - Slider configuration console to manage homepage promotional banners, display ordering, and link destinations.
  - Dedicated slider editor supporting banner aspect-ratio previews and display sequences.
- **🛡️ Role-Based Access Control (RBAC):**
  - Granular role definitions (Admin, Editor, Warehouse Manager) to regulate administrative privileges.
  - Role management dashboard displaying assigned personnel counts and permission summaries.
- **👥 Personnel & User Administration:**
  - User records table detailing team member profiles, email addresses, assigned roles, and registration timestamps.
  - New user registration forms with role allocation and credential management.
- **🚚 Order Fulfillment & Detailed Receipts:**
  - Complete order processing pipeline tracking pending, packaged, shipped, and completed deliveries.
  - Deep-dive order detail view featuring customer billing details, shipping addresses, purchased item lists, unit pricing, tax calculations, and total amounts.
- **👤 Profile Settings & Authentication:**
  - Admin account customization hub for updating personal credentials, contact details, and password security.
  - Clean, dedicated login gateway with error alerts and form validation states.
- **🎨 Curated Brand Visual Identity:**
  - Signature Halikarnas Emerald navbar (`#519d79` with `#3f7b5f` borders) harmonized with rich berry accent buttons (`#9d5175`).
  - Elevated card containers, subtle borders, soft drop shadows, and horizontally scrollable responsive data tables.
- **⚡ High Performance & Zero Build Overhead:**
  - Pure static front-end architecture with zero compilation dependencies, instant page transitions, and minimal asset footprints.

---

## 🛠️ Tech Stack

| Technology | Purpose |
| :--- | :--- |
| **HTML5** | Semantic web layout across 14 administrative pages and modules |
| **CSS3** | Custom design tokens, button states, image preview boxes, and responsive media queries |
| **Bootstrap 5.3.3** | Responsive grid, interactive dropdowns, navigation togglers, alerts, and modal elements |
| **Font Awesome 6.7.2** | Comprehensive vector iconography for KPI metrics, actions, and status badges |
| **GitHub Actions** | Automated CI/CD workflow for continuous deployment to GitHub Pages |
| **GitHub Pages** | High-availability global static site hosting |

---

## 📁 Project Structure

```text
halikarnasInventoryTracking/
├── .github/
│   └── workflows/
│       └── deploy.yml          # GitHub Actions workflow for automatic GitHub Pages deployment
├── img/                        # Product photographs, slider banners, and user avatar assets
├── .gitignore                  # Git ignore rules for system and editor artifacts
├── hesabim.html                # Admin account profile & security settings
├── index.html                  # Main administrative dashboard with KPI metrics & order summary
├── kategori.html               # Category list table with thumbnail & product count
├── kategori-ekle.html          # Category creation & editing form
├── kullanici.html              # System users list & role assignments
├── kullanici-ekle.html         # User creation form with role selector
├── LICENSE                     # MIT License documentation
├── login.html                  # Admin authentication & login screen
├── README.md                   # Comprehensive project documentation
├── role.html                   # Role definitions & access privileges table
├── siparis.html                # Orders pipeline table with status badges
├── siparis-detay.html          # Detailed order invoice, shipping info & item breakdown
├── slider.html                 # Homepage promotional slider management table
├── slider-ekle.html            # Slider image banner creation & editing form
├── style.css                   # Custom brand tokens, primary button styles & responsive table rules
├── urun.html                   # Full product catalog & stock inventory table
└── urun-ekle.html              # Product creation form with image preview & pricing controls
```

---

## 🚀 Getting Started

To explore or run this project locally on your machine:

### 1. Clone the Repository

```bash
git clone https://github.com/kucukagtas/halikarnasInventoryTracking.git
```

### 2. Navigate to the Project Directory

```bash
cd halikarnasInventoryTracking
```

### 3. Run Locally

Since this is a pure static web application, you can run it directly without any build tools or runtime environments:

* **Directly in Browser:** Double-click `index.html` or open it with any modern web browser (Chrome, Safari, Firefox, Edge).
* **VS Code Live Server:** Right-click `index.html` and select **"Open with Live Server"**.
* **Via Node.js `serve`:**
  ```bash
  npx serve .
  ```
* **Via Python HTTP Server:**
  ```bash
  python3 -m http.server 8000
  ```

---

## 🌐 Deployment

The live version of **Halikarnas Inventory Tracking** is deployed on **GitHub Pages**:

👉 **[https://kucukagtas.github.io/halikarnasInventoryTracking/](https://kucukagtas.github.io/halikarnasInventoryTracking/)**

---

## 📄 License

This project is open-source and licensed under the [MIT License](LICENSE) — see the [LICENSE](LICENSE) file for details.

Copyright © 2026 [Muhammed Küçükağtaş](https://github.com/kucukagtas). All rights reserved.
