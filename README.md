# 🚀 Official APK Releases & Product Distribution Hub

Welcome to the central release repository for applications, tools, mobile APKs, browser extensions, and web services created by **[Mohd-afk](https://github.com/Mohd-afk)**. 

This repository hosts official compiled binaries (Android `.apk` packages), browser extensions, web application portals, and comprehensive guides for setup and installation.

---

## 🌟 Featured Applications & Releases

| Application | Category | Latest Release | Platform | Direct APK / Link | Documentation |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 🛡️ **KeeGuard** | Security & Password Manager | `v5.0.3` | Android, Web, Extension | [Download APK](https://github.com/Mohd-afk/apk-releases/releases/tag/v5.0.3) | [KeeGuard Guide](USERGUIDE.md#1-installing-the-android-apk-on-mobile) |
| 🏷️ **ShipLabel (LabelForge / ERPLite)** | E-Commerce & Shipping | `v1.0.9` | Web, Desktop Utility | [Open Web App](https://github.com/Mohd-afk/LABELPDF) | [ShipLabel Guide](USERGUIDE.md#3-using-the-web-applications) |
| 🍔 **Smart Food Deal Extension** | Savings & Automation | `v1.0.0` | Chrome, Edge, Brave | [View Repo](https://github.com/Mohd-afk/foodextension) | [Extension Guide](USERGUIDE.md#2-installing-the-browser-extension) |
| 🧭 **SortPilot** | Inventory & Data Tools | `v1.0.0` | Web Utility | [View Repo](https://github.com/Mohd-afk/SORTPILOT) | [SortPilot Info](#-sortpilot) |

---

## 📱 Detailed Product Showcase

### 🛡️ KeeGuard — Password Manager & Vault Suite
> **Zero-Knowledge, Military-Grade Encrypted Password Manager & Autofill Framework**

KeeGuard is an end-to-end encrypted password manager offering native Android application support with system-wide Autofill integration, browser extension support, and a high-performance web vault dashboard.

- **Key Features:**
  - 🔒 **Zero-Knowledge Encryption:** Client-side AES-256-GCM encryption with PBKDF2 key derivation.
  - 📱 **Android System Autofill:** Native integration with Android's `AutofillService` framework.
  - 🎨 **Custom Profile Mapping:** Dynamic field mapping and auto-renaming protection for complex login forms.
  - 🔑 **Biometric Unlock:** Fingerprint and Face ID support on supported mobile hardware.
  - 🌐 **Web Vault & Admin Portal:** Full web accessibility with modern dark-mode UI.
- **Repository:** [`Mohd-afk/securevault-app`](https://github.com/Mohd-afk/securevault-app)
- **Latest Release:** [KeeGuard v5.0.3 Release Notes & APK Assets](https://github.com/Mohd-afk/apk-releases/releases/tag/v5.0.3)

---

### 🏷️ ShipLabel / LabelForge (ERPLite)
> **Automated E-Commerce Order & Shipping Label Generator**

ShipLabel (LabelForge / ERPLite) simplifies shipping operations for e-commerce sellers by processing order manifests, formatting thermal labels, and calculating inventory reorder metrics.

- **Key Features:**
  - 📦 **Thermal Label Formatting:** Instant transformation of raw shipping labels into optimized 4x6 thermal printer format.
  - 📊 **Order Status Matrix:** Live order tracking across Pending, Packed, Shipped, and Delivered states.
  - 📈 **Dynamic Inventory Forecasting:** Reorder warnings and stock management integrated into a unified dashboard.
- **Repository:** [`Mohd-afk/LABELPDF`](https://github.com/Mohd-afk/LABELPDF) / [`Mohd-afk/ERPLITE`](https://github.com/Mohd-afk/ERPLITE)

---

### 🍔 Smart Food Deal Extension
> **Automated Food Delivery Coupon & Discount Aggregator**

A Manifest V3 browser extension designed for Chrome, Brave, and Edge that scans Swiggy and Zomato for exclusive restaurant deals and top savings without requiring account credentials.

- **Key Features:**
  - ⚡ **Instant Deal Detection:** Automatically flags first-order discounts and stacked promo codes.
  - 🔒 **Privacy First:** Operates entirely within your local browser sandbox.
  - 🎯 **One-Click Filtering:** Ranks active deals by total savings percentage.
- **Repository:** [`Mohd-afk/foodextension`](https://github.com/Mohd-afk/foodextension)

---

### 🧭 SortPilot
> **High-Efficiency Data & Inventory Sorting Engine**

SortPilot is a specialized utility tool designed for sorting algorithms, item classification, and automated batch file management.

- **Repository:** [`Mohd-afk/SORTPILOT`](https://github.com/Mohd-afk/SORTPILOT)

---

## 📘 Step-by-Step Installation & User Guide

For detailed step-by-step instructions on how to install and use any of our applications, visit the comprehensive **[USERGUIDE.md](USERGUIDE.md)**:

1. 📱 **[Android APK Sideloading Guide](USERGUIDE.md#1-installing-the-android-apk-on-mobile)** — Enable unknown sources, handle Play Protect warnings, and activate Autofill.
2. 🧩 **[Browser Extension Guide](USERGUIDE.md#2-installing-the-browser-extension)** — Enable Developer Mode and load unpacked extensions.
3. 🌐 **[Web Application Guide](USERGUIDE.md#3-using-the-web-applications)** — Access and use web portals and cloud sync features.
4. 🛠️ **[Troubleshooting & FAQ](USERGUIDE.md#4-troubleshooting--faq)** — Frequently encountered questions and resolution steps.

---

## 🔒 Security & Verification

All APK binaries published in [Releases](https://github.com/Mohd-afk/apk-releases/releases) are built directly from open-source repositories. 

To verify the checksum of a downloaded `.apk` file on your machine:

```bash
# On Linux / macOS
sha256sum app-debug.apk

# On Windows PowerShell
Get-FileHash -Algorithm SHA256 .\app-debug.apk
```

---

## 🤝 Support & Feedback

If you encounter issues during installation or have feature requests:
- Open an Issue in the [apk-releases Issues](https://github.com/Mohd-afk/apk-releases/issues) page.
- Refer to the [Troubleshooting Guide](USERGUIDE.md#4-troubleshooting--faq).

© 2026 **Mohd-afk** — All rights reserved.
