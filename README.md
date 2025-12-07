# 🎓 Campus Tracker

<div align="center">

![Campus Tracker Banner](https://images.unsplash.com/photo-1541339907198-e08756dedf3f?w=1920&q=80)

### *Reuniting Lost Items with Their Owners Through Smart Technology*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

[🚀 Live Demo](#) • [📖 Documentation](#features) • [🐛 Report Bug](https://github.com/yourusername/campus-tracker/issues) • [✨ Request Feature](https://github.com/yourusername/campus-tracker/issues)

</div>

---

## 📋 Table of Contents

- [Overview](#-overview)
- [Features](#-features)
- [Screenshots](#-screenshots)
- [Technology Stack](#-technology-stack)
- [Getting Started](#-getting-started)
- [Usage Guide](#-usage-guide)
- [Project Structure](#-project-structure)
- [Contributing](#-contributing)
- [License](#-license)

---

## 🌟 Overview

**Campus Tracker** is a comprehensive web-based platform designed to help students, faculty, and staff report and recover lost items on campus. With an intuitive interface and smart matching algorithms, we make it easier than ever to reunite people with their belongings.

### 🎯 Problem Statement

Every year, thousands of items are lost on college campuses with no efficient system to track and return them. Campus Tracker bridges this gap by providing:

- ✅ Centralized reporting system for lost & found items
- ✅ AI-powered matching between lost and found items
- ✅ Secure messaging for privacy-protected communication
- ✅ Administrative oversight for content moderation
- ✅ Real-time notifications and updates

---

## ✨ Features

### 🔍 Core Functionality

| Feature | Description |
|---------|-------------|
| **📝 Lost Item Reporting** | Report items you've lost with detailed descriptions, images, and location data |
| **🔎 Found Item Reporting** | Submit found items to help others recover their belongings |
| **🎯 AI Matching System** | Smart algorithm matches lost items with found items based on descriptions and images |
| **💬 Secure Messaging** | Privacy-protected chat system with masked contact information |
| **🔔 Real-time Notifications** | Get instant alerts when potential matches are found |
| **👨‍💼 Admin Dashboard** | Comprehensive moderation tools for platform administrators |

### 🎨 User Experience

- **Responsive Design** - Works seamlessly on desktop, tablet, and mobile devices
- **Modern UI/UX** - Clean, intuitive interface with smooth animations
- **Dark/Light Themes** - Customizable viewing experience
- **Image Upload** - Visual identification with drag-and-drop support
- **Search & Filter** - Quickly find items by category, location, or date

### 🔐 Security Features

- Email verification for user registration
- Privacy-masked contact information
- Admin content moderation
- Spam detection and flagging system
- Secure data handling


## 🛠️ Technology Stack

<div align="center">

| Frontend | Styling | Features |
|:--------:|:-------:|:--------:|
| ![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) | ![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat-square&logo=css3) | ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) |
| Semantic HTML | Custom CSS Grid | Vanilla JavaScript |
| Accessibility | Flexbox Layouts | ES6+ Features |
| SEO Optimized | Animations | Event Handling |

</div>

### 📦 Key Libraries & Tools

- **Google Fonts** - Inter font family for modern typography
- **Unsplash** - High-quality background imagery
- **SVG Icons** - Scalable vector graphics for crisp icons
- **LocalStorage** - Client-side data persistence
- **FileReader API** - Image upload and preview

---

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- Basic text editor or IDE
- Local web server (optional, for testing)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/campus-tracker.git
   cd campus-tracker
   ```

2. **Open the project**
   ```bash
   # Simply open index.html in your browser
   # OR use a local server
   python -m http.server 8000
   # OR
   npx serve
   ```

3. **Access the application**
   - Direct: `file:///path/to/index.html`
   - Server: `http://localhost:8000`

### 🎮 Quick Start

```javascript
// No build process required!
// Just open index.html and you're ready to go

// Demo Credentials (for testing)
Email: demo@campus.edu
Password: demo123
```

---

## 📖 Usage Guide

### For Students & Staff

#### 🔴 Reporting a Lost Item

1. Navigate to the **Lost Items** section
2. Fill out the form with:
   - User type (Student/Teacher/Staff/Worker)
   - Your name and contact email
   - Item details (name, category, description)
   - Location where lost
   - Optional: Upload an image
3. Click **Submit Lost Item Report**
4. Receive notifications if matches are found

#### 🟢 Reporting a Found Item

1. Go to the **Found Items** section
2. Complete the form including:
   - Item information and description
   - Location where found
   - **Required:** Upload a clear image
3. Submit and help reunite items with owners

#### 🎯 Using the Matching System

1. Visit the **Match Items** section
2. Upload a reference image of your lost item
3. Provide detailed description
4. View AI-generated matches with percentage scores
5. Contact finders through secure messaging

### For Administrators

#### 🛡️ Admin Panel Features

- **Dashboard Overview** - View statistics and metrics
- **Post Moderation** - Approve, edit, or delete posts
- **Flagged Content** - Review and resolve reported items
- **User Management** - Monitor platform activity
- **Search & Filter** - Find specific posts quickly

---

## 📁 Project Structure

```
campus-tracker/
│
├── index.html              # Main HTML file
│
├── assets/
│   ├── images/            # Image assets
│   └── icons/             # SVG icons
│
├── styles/
│   ├── main.css           # Core styles (embedded in HTML)
│   └── responsive.css     # Media queries
│
├── scripts/
│   ├── app.js             # Main JavaScript (embedded in HTML)
│   ├── auth.js            # Authentication logic
│   ├── items.js           # Item management
│   ├── matching.js        # AI matching algorithm
│   └── admin.js           # Admin functions
│
├── README.md              # This file
├── LICENSE                # MIT License
└── CONTRIBUTING.md        # Contribution guidelines
```

---

## 🎨 Design System

### Color Palette

```css
--primary-color: #fabc11;    /* Bright Yellow */
--primary-dark: #ff0000;     /* Red Accent */
--text-primary: #ff0b0b;     /* Primary Text */
--text-secondary: #0a0a0b;   /* Secondary Text */
--bg-primary: #ffffff;       /* White Background */
```

### Typography

- **Font Family:** Inter (Google Fonts)
- **Weights:** 300, 400, 500, 600, 700
- **Base Size:** 16px
- **Line Height:** 1.6

---

</div>
