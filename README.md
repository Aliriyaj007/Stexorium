# 🔐 Stexorium

![Version](https://img.shields.io/badge/version-v1.0.0-blue)
![Status](https://img.shields.io/badge/status-stable-success)
![Usage](https://img.shields.io/badge/license-personal--use--only-orange)
![Tech](https://img.shields.io/badge/tech-client--side%20only-lightgrey)

**Stexorium** is a focused, single-file privacy utility for encrypting sensitive text and optionally hiding it inside images — entirely **client-side**, with **no backend**, **no accounts**, and **no data leaving your device**.

This project exists to remove friction from a very specific problem:

> **Securely encrypt small pieces of sensitive information without installing software or trusting a server.**

If you can open a browser, you can use Stexorium.

---

## 🧠 Why This Tool Exists

**Before Stexorium**

* You rely on online tools whose servers you don’t control
* You install heavyweight applications for simple encryption
* You share encrypted text that obviously *looks* encrypted

**After Stexorium**

* Encryption runs locally in your browser
* One HTML file does everything
* Encrypted data can be hidden inside ordinary images

| Problem               | Typical Tools | Stexorium |
| --------------------- | ------------- | --------- |
| Requires server       | ❌             | ✅ No      |
| Works offline         | ❌             | ✅ Yes     |
| Installation needed   | ❌             | ✅ No      |
| Image-based hiding    | ❌             | ✅ Yes     |
| Single-file longevity | ❌             | ✅ Yes     |

---

## ⚡ What Stexorium Does

| Feature                | Description                                          |
| ---------------------- | ---------------------------------------------------- |
| AES-256-GCM Encryption | Modern authenticated encryption using Web Crypto API |
| PBKDF2 Key Derivation  | 250,000 iterations with random salt                  |
| Image Steganography    | Hide encrypted data inside images (LSB, RGB)         |
| QR Codes               | Encode encrypted payloads visually                   |
| QR Scanning            | Recover encrypted data from QR images                |
| Panic Mode             | Instantly wipe UI and exit                           |
| Offline-First          | Works without internet (optional local setup)        |
| Single HTML File       | Long-term, dependency-light utility                  |

---

## 🚀 60-Second Usage

1. Open the web app or the local HTML file
2. Enter a strong password
3. Paste the text you want to protect
4. Click **Encrypt**
5. (Optional) Embed the encrypted output into an image
6. Save the `.key` file, QR code, or stego image

That’s it.

No setup. No accounts. No tracking.

---

## 🛠 Installation Options

### Option 1 — Use the Web App

➡️ **Live Web App**: [https://aliriyaj007.github.io/Stexorium/](https://aliriyaj007.github.io/Stexorium/)

Open and use instantly.

---

### Option 2 — Download & Run Locally (Recommended)

1. Download the repository or the HTML file
2. Open `index.html` in any modern browser
3. Use completely offline

**No build step required.**

---

### Option 3 — Fully Offline (QR & Markdown Support)

For full offline support:

1. Download these libraries:

   * `qrcode.min.js`
   * `jsQR.min.js`
   * `marked.min.js`
2. Place them next to the HTML file
3. Update script paths to local files

Encryption and steganography work even without these extras.

---

## 🔐 Security Model (Read This)

### What Stexorium Protects Against

* Accidental data exposure
* Plaintext storage
* Network-based data leaks

### What It Does **Not** Protect Against

* Malware or keyloggers
* Compromised browsers or OS
* Advanced steganalysis
* Lost passwords

> If your device is compromised, no browser-based encryption tool can help.

---

## 🔑 Password Guidance

* Use long passphrases (generated phrases are recommended)
* Password strength meter provides **approximate entropy estimation**
* **Passwords are never recoverable**

---

## 📦 Project Status

| Attribute    | Value                  |
| ------------ | ---------------------- |
| Version      | v1.0.0                 |
| Stability    | Frozen (stable)        |
| Updates      | Security fixes only    |
| Intended Use | Personal / Educational |

---

## 📜 License — Personal Use Only

This project is **not open-source**.

You **may**:

* Use it for personal, non-commercial purposes
* Study and modify the code privately

You **may not**:

* Use it commercially or professionally
* Redistribute or resell the code
* Include it in paid tools, courses, or services

📩 Commercial or professional use requires explicit permission.

---

## 🤝 Contributions

Contributions are welcome **for fixes, documentation improvements, or security hardening**.

If you submit a PR:

* Keep it minimal
* Avoid feature bloat
* Respect the project’s personal-use scope

---

## 👤 Author & Contact

**Author:** Riyajul Ali
**GitHub:** [https://github.com/Aliriyaj007](https://github.com/Aliriyaj007)

**Email:** [aliriyaj007@protonmail.com](mailto:aliriyaj007@protonmail.com)

**LinkedIn:** [https://linkedin.com/in/Aliriyaj007](https://linkedin.com/in/Aliriyaj007)

**Direct Download:** 
**Web App:** [https://aliriyaj007.github.io/Stexorium/](https://aliriyaj007.github.io/Stexorium/)

---

> *Small tools. Local trust. Long-term utility.*
