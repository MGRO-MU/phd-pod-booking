# PhD Pod Booking System 🎓

A streamlined, mobile-first web application designed to manage room bookings for the **"PhD Pod"** quiet space at the PhD Hub, Monash University. This system simplifies the reservation process for students via QR code access and provides MGRO administrators with powerful insights into space utilization.

## 🚀 Key Features

### For Students (User)
* **📱 Mobile-First Design:** Optimized for smartphones; students can book instantly by scanning a QR code.
* **⚡ Instant Booking:** Simple form requiring Name, Student ID, and Monash Email.
* **📅 Real-Time Availability:** Prevents double-booking by checking live schedule data.
* **🔐 Self-Service Management:** Students create a secure 4-digit PIN to **Modify** or **Cancel** their bookings without needing admin assistance.

### For Administrators (MGRO)
* **🛡️ Secure Dashboard:** Protected admin area 
* **📊 Analytics Intelligence:**
* **📥 Data Export:** Download complete booking history to **CSV (Excel)** for reporting.
* **⚙️ Admin Settings:** Manage passwords and delete bookings directly from the interface.

## 🛠️ Technology Stack

Designed for **longevity and zero maintenance**. This project uses a "Serverless" and "Buildless" architecture:

* **Frontend:** HTML5, Tailwind CSS (via CDN), React.js (via CDN).
* **Backend:** Google Firebase.
* **Auth:** Firebase Anonymous Authentication.

## 📦 Deployment Guide

This application is a **static single-file** web app, making it incredibly easy to host anywhere.

### Option 1: GitHub Pages (Recommended)
1.  Upload `index.html` to the repository.
2.  Go to **Settings** > **Pages**.
3.  Under "Build and deployment", select the `main` branch.
4.  Click **Save**. Your site is live!

### Option 2: University Servers
Simply upload the `index.html` file to any standard web server directory. No database configuration on the server is required (it connects directly to Google Cloud).

---

📧 Technical Contact: [yayan.riyanto@monash.edu](mailto:yayan.riyanto@monash.edu)
<br>
<br>
*© 2026. Created for the Monash Graduate Research Office (MGRO).*
