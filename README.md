# 🛡️ Perform a Basic Vulnerability Scan on Your PC using Nessus (Windows)

## 📋 Overview

This guide provides step-by-step instructions to **install**, **configure**, and **perform a basic vulnerability scan** on a Windows PC using **Tenable Nessus**, a powerful vulnerability assessment tool used by security professionals worldwide.

---

## ✅ Prerequisites

* A PC running **Windows 10 or later**
* **Administrative privileges** on your system
* An active **internet connection**
* A valid email address (for Nessus Essentials license activation)

---

## 📦 Installation Steps

1. **Download Nessus**

   * Go to: [https://www.tenable.com/products/nessus/nessus-essentials](https://www.tenable.com/products/nessus/nessus-essentials)
   * Choose **Nessus Essentials** and select **Windows** as the platform.
   * Register with your email to receive the **activation code**.

2. **Install Nessus**

   * Run the downloaded `.exe` file.
   * Follow the on-screen prompts to complete installation.

3. **Start Nessus**

   * Once installed, Nessus opens in your default browser at:
     `https://localhost:8834`
   * Create an admin user.
   * Enter the **activation code** received via email.
   * Wait for Nessus to download and compile plugins (may take 10–20 minutes).

---

## 🧪 Performing a Basic Vulnerability Scan

1. **Log into the Nessus Web Interface**

   * Go to `https://localhost:8834` in your browser.

2. **Create a New Scan**

   * Click **"New Scan"** > Select **"Basic Network Scan"**.
   * Name your scan (e.g., `Local_PC_Scan`).
   * Set the target as your PC's IP address (e.g., `127.0.0.1` or local IP).

3. **Configure Settings**

   * Leave default settings unless advanced configuration is needed.
   * (Optional) Customize ports, plugins, or use credentials for deeper scanning.

4. **Launch the Scan**

   * Click **"Save"** then **"Launch"**.
   * Monitor scan progress from the dashboard.

5. **View Results**

   * Click on the scan to view a summary of discovered vulnerabilities.
   * Export the report (HTML, PDF, CSV) if needed.

---

## 📊 Sample Output

* **Critical Vulnerabilities**: 1
* **High Vulnerabilities**: 3
* **Medium Vulnerabilities**: 6
* **Low Vulnerabilities**: 5
* **Informational**: 15

Each finding includes:

* Plugin ID
* Vulnerability Name
* Description
* Risk Factor
* Recommended Fix

---

## 🔐 Recommendations

* **Apply system updates** immediately.
* **Disable outdated protocols** (e.g., SMBv1).
* **Replace self-signed certificates**.
* **Limit open ports** and unused services.
* **Schedule periodic scans**.

---

## 🧑‍💻 Author

* **Name:** *Beta Chandra sekhar*
* **Date:** *june 26 2025*
* **Contact:** *betachandrasekhar@gmail.com*

---
