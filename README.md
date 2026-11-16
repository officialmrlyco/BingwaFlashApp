<div align="center">

<img src="https://bingwaflash.co.ke/logo.png" alt="BingwaFlash Logo" width="120" />

# BingwaFlash

### *The Ultimate USSD & M-PESA Automation Assistant for Bingwa & Safaricom Agents*

[![Platform](https://img.shields.io/badge/Platform-Android-green.svg?style=for-the-badge&logo=android)](https://github.com/officialmrlyco/BingwaFlashApp/releases)
[![Version](https://img.shields.io/badge/Version-v1.4.4%20(Build%2044)-yellow.svg?style=for-the-badge)](https://github.com/officialmrlyco/BingwaFlashApp/releases/download/v44/BingwaFlash_v1.4.4.apk)
[![Target](https://img.shields.io/badge/For-Safaricom%20%26%20Bingwa%20Agents-red.svg?style=for-the-badge)](https://bingwaflash.co.ke)
[![Status](https://img.shields.io/badge/Status-Active-brightgreen.svg?style=for-the-badge)]()
[![Releases](https://img.shields.io/badge/Download-v1.4.4%20APK-blue.svg?style=for-the-badge)](https://github.com/officialmrlyco/BingwaFlashApp/releases/download/v44/BingwaFlash_v1.4.4.apk)

---

**Streamline your airtime and data bundle business with 100% automated USSD execution and instant M-PESA payment processing.**

[Features](#-key-features) • [How It Works](#-how-it-works) • [Installation](#-getting-started) • [Permissions](#-permissions--security) • [Privacy Policy](https://bingwaflash.co.ke/privacy) • [Terms of Service](https://bingwaflash.co.ke/terms) • [Support](#-support--contact)

---

</div>

## 📌 Overview

**BingwaFlash** is a high-speed, intelligent automation application designed specifically for **Safaricom and Bingwa Sokoni agents** across Kenya. 

Managing manual USSD dialing while trying to process hundreds of customer airtime and bundle orders is slow, tiring, and prone to human error. **BingwaFlash eliminates the manual work completely.** The moment a customer pays you via M-PESA, BingwaFlash reads the payment, matches the requested offer, automatically dials the USSD code, and completes the transaction—all in a matter of seconds.

---

## ✨ Key Features

### ⚡ 1. Fully Automated USSD Execution
- No more manually typing `*180#` or `*140#` or navigating multi-level USSD menus.
- Hands-free processing of airtime and data bundle purchases.
- Supports **Direct**, **Simple**, and **Advanced** USSD execution modes tailored to your device's speed.

### 📩 2. Instant M-PESA Payment Detection
- Automatically detects incoming M-PESA confirmation SMS messages (Till, PayBill, or P2P).
- Matches the received amount directly to the customer's requested product.
- Processes the order automatically without requiring agent intervention.

### 🔄 3. Smart Queue & Failure Recovery
- **Zero Lost Funds**: If a USSD attempt fails (due to network busy, insufficient float, or wrong PIN), the transaction is immediately saved to a **Pending Hold** queue.
- Review failed or held transactions directly from the **Recovery Prompt** screen and retry with a single tap when ready.
- Never accidentally double-charge or lose track of an unfulfilled customer.

### 📊 4. Real-Time Sales & Earnings Dashboard
- Track your **total revenue**, **daily profit**, and **earned commissions** instantly.
- Filter transactions by date, status (Completed, Pending, Failed), or customer number.
- Export transaction logs and customer data directly to CSV for easy record-keeping.

### 👥 5. Built-in Client & Debt Management
- Keep a neatly organized list of your repeat customers.
- Automatically track customer debts and overpayments.
- When a customer pays a pending debt via M-PESA, BingwaFlash automatically registers the payment and clears their balance before issuing new airtime.

### 🌐 6. Web Orders & Remote Portal Integration
- Allow your customers to place orders remotely online via your custom web link.
- Synchronize your web orders, token balance, and live stock with the BingwaFlash Agent Portal.

### 📱 7. Multi-SIM & Dual-Standby Support
- Easily assign specific SIM slots (SIM 1 or SIM 2) for different types of transactions or airtime checks, with full dual-profile / eSIM support.

### 📣 8. Automated SMS Marketer & Shop Loyalty (New in v1.4.4)
- **Automated SMS Marketer**: 13 intelligent repeat-purchase, win-back, streak, points, and time-of-day strategies powered by a multi-part message bank with thousands of natural variations, daily customer caps (up to 2,000/day), and a dedicated **Stop Offers** screen.
- **Shop Loyalty (Streaks & Referrals)**: Reward loyal customers automatically with streak milestones, referral bonuses, and interactive SMS commands (`SHOP`, `POINTS`, `STREAKS`, `REF`).
- **Safaricom Carrier Error Alerts**: Instant Agent Alerts when a customer's SIM is inactive or when Bingwa returns a carrier purchase error.

---

## 🆕 Latest Release — v1.4.4 (Build 44)

- **Direct APK Download**: [BingwaFlash_v1.4.4.apk (17.3 MB)](https://github.com/officialmrlyco/BingwaFlashApp/releases/download/v44/BingwaFlash_v1.4.4.apk)
- **SHA-256 Checksum**: `803ed539574c9dc71c8c7eaa02489f45430f96df0b511df4958f16dcc1be19ec`
- **File Size**: `18,168,806` bytes (17.3 MB)

---

## 🛠️ How It Works

```
   ┌────────────────┐      ┌────────────────┐      ┌────────────────┐      ┌────────────────┐
   │ Customer Pays  │ ───► │  M-PESA SMS    │ ───► │  BingwaFlash   │ ───► │  USSD Fulfills │
   │   via M-PESA   │      │   Received     │      │ Auto-Processes  │      │ Customer Order │
   └────────────────┘      └────────────────┘      └────────────────┘      └────────────────┘
```

1. **Receive Payment**: Customer sends M-PESA payment for their desired airtime/data package.
2. **Instant Match**: BingwaFlash reads the SMS, verifies the amount, and matches it with the correct USSD offer code.
3. **Auto-Execution**: The app automatically opens the USSD channel, dials the codes, and completes the purchase in seconds.
4. **Instant Confirmation**: The customer receives their airtime/data instantly, and your dashboard updates in real-time.

---

## 🚀 Getting Started

### 📥 Step 1: Download the App
Head over to the **[Official Releases Page](https://github.com/officialmrlyco/BingwaFlashApp/releases)** and download the latest `.apk` file directly to your Android device.

> **Note**: If downloading for the first time, your browser may ask for permission to "Install apps from unknown sources". Allow this setting to complete the installation.

### ⚙️ Step 2: Grant Permissions
To perform hands-free automation, BingwaFlash requires a few essential Android permissions:
- **Accessibility Service**: Enables the app to read and interact with USSD dialog pop-ups automatically.
- **SMS Permission**: Allows the app to detect incoming M-PESA payment notifications.
- **Phone / Call Permission**: Required to place USSD calls on your behalf.
- **Overlay Permission**: Displays status indicators and prompt dialogs over other applications.

### ⚙️ Step 3: Configure & Start
1. Open BingwaFlash and log in to your agent account.
2. Select your preferred **SIM Slot** for USSD execution.
3. Turn on the **Automation Switch** on the main dashboard.
4. You're ready to go! Leave the app running in the background and watch your orders get processed automatically.

---

## 🔒 Permissions & Privacy

BingwaFlash is designed with **privacy and security** as top priorities:

| Permission | Why It's Needed |
| :--- | :--- |
| **Accessibility Service** | To detect and click buttons on USSD pop-up screens automatically. |
| **Read/Receive SMS** | To detect M-PESA confirmation messages for automatic order matching. |
| **Make & Manage Calls** | To send USSD requests directly to the network provider. |
| **Display Over Other Apps** | To display transaction alerts and progress pop-ups. |

* **Data Safety**: BingwaFlash only reads M-PESA transaction messages from Safaricom. Personal messages are strictly ignored.
* **Privacy Policy**: Read our full [Privacy Policy](https://bingwaflash.co.ke/privacy).
* **Terms of Service**: Read our [Terms of Service](https://bingwaflash.co.ke/terms).

---

## 📱 Device Requirements

- **Operating System**: Android 8.0 (Oreo) or higher.
- **Network**: Active SIM card supporting USSD codes and M-PESA SMS.
- **Device**: Any standard Android smartphone.

---

## 📩 Support & Contact

If you have questions, need assistance, or want to report an issue, we're here to help:

* **Official Website**: [bingwaflash.co.ke](https://bingwaflash.co.ke)
* **Direct Downloads**: [download.bingwaflash.co.ke](https://download.bingwaflash.co.ke)
* **Terms & Conditions**: [bingwaflash.co.ke/terms](https://bingwaflash.co.ke/terms)
* **Privacy Policy**: [bingwaflash.co.ke/privacy](https://bingwaflash.co.ke/privacy)
* **Support Email**: `support@bingwaflash.co.ke`

---

<div align="center">

**[ 🚀 Download the Latest Release Here ](https://github.com/officialmrlyco/BingwaFlashApp/releases)**

*Empowering Agents with Speed, Accuracy, and Automation.*

</div>
