# 🧾 SmartReceipt

**SmartReceipt** is a lightweight, offline-capable web application for generating, sharing, and managing professional receipts.  
It includes a secure admin area for license management and a responsive interface that works across all devices.

---

## 🚀 Features

### 💼 For Users
- Generate digital receipts with:
  - Business Name
  - Payer Name
  - Amounts (Total, Paid, Arrears)
  - Purpose and Date
- Export as PDF or copy/share via WhatsApp
- Email + License key activation system
- Fully responsive interface (mobile-friendly)

### 🔐 For Admins
- Access admin panel via **triple-click** on the title (PIN required)
- Manage all users and license keys:
  - View user email, license key, activation date, and expiry date
  - Auto-generate keys (format: `SR-XXXX-XXXX-XXXX`)
  - Choose license durations (15, 30, or 60 days)
  - Delete or manually add activations
- Solid dark background for clarity
- Data stored locally with `localStorage`

---

## 🧱 Tech Stack
- **Frontend:** HTML5, CSS3, JavaScript (Vanilla)
- **Storage:** LocalStorage API (no backend required)
- **Libraries:**
  - [jsPDF](https://github.com/parallax/jsPDF) – PDF generation
  - Native Web APIs – Clipboard, Local Storage, Modal handling

---

## 🧩 Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/YOUR-USERNAME/SmartReceipt.git
