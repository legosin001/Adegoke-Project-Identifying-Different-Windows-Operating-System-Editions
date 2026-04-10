# 🪟 Adegoke Project — Identifying Different Windows Operating System Editions

![Project](https://img.shields.io/badge/Adegoke-Project-6A0DAD?style=for-the-badge)
![Score](https://img.shields.io/badge/Quiz%20Score-5%2F5%20%28100%25%29-brightgreen?style=for-the-badge)
![Platform](https://img.shields.io/badge/Platform-Practice%20Labs-0078D4?style=for-the-badge)
![OS](https://img.shields.io/badge/OS-Windows%2011-0078D4?style=for-the-badge&logo=windows&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

---

## 📋 Project Overview

This repository documents a **hands-on lab** focused on identifying and distinguishing between different Windows Operating System editions. Working across multiple virtual machines running different Windows versions, I explored how to locate edition information, identify edition-specific features, and understand the differences between Home, Pro, and Enterprise editions.

 
> 📅 **Completed:** October 2025

---

## 🎯 What This Lab Covers

Understanding Windows editions is a core IT support skill. This lab works through:

- Identifying the **Windows edition, version, and OS build** via Settings → System → About
- Locating **BitLocker Drive Encryption** — a feature exclusive to Windows Pro and Enterprise
- Distinguishing between **Windows 11 Home** and **Windows 11 Pro** on different machines
- Using the `winver` command to quickly check Windows version information
- Understanding **maximum RAM and storage limits** per edition
- Knowing which features are **edition-specific** (e.g. BitLocker, Group Policy, Remote Desktop hosting)

---

## 🧪 Lab Tasks

| # | Task | Description | Status |
|---|------|-------------|--------|
| 1 | Identify Windows 11 Pro system specs | View System → About on PLABWIN11 — confirmed Windows 11 Pro, Version 21H2, 8GB RAM | ✅ Complete |
| 2 | Locate BitLocker on a Pro machine | Search for BitLocker via Start — confirmed available on Windows 11 Pro | ✅ Complete |
| 3 | Identify Windows 11 Home on second machine | View Activation settings on PLABWIN11HOME — confirmed Windows 11 Home edition | ✅ Complete |

---

## 📸 Screenshots — Evidence of Completion

**Windows 11 Pro — System > About showing edition, version, build, and hardware specs:**

![01_Windows11_Pro_System_About](https://github.com/user-attachments/assets/6cf8af7c-4dfa-4d7b-9f98-4adb06774d8e)



---

**BitLocker Drive Encryption — available via Start search on Windows 11 Pro (Pro/Enterprise exclusive feature):**

![02_BitLocker_Search](https://github.com/user-attachments/assets/83510bea-545f-4583-bdb5-fabe68103500)


---

**Windows 11 Home — System > Activation confirming Home edition on second virtual machine:**

![03_Windows11_Home_Activation](https://github.com/user-attachments/assets/57a5db31-8ee1-45ac-b325-3150173f0cfb)


---

## ❓ Quick Fire — Test Your Knowledge

If you've worked through this project, you should be able to answer these without hesitation. Give it a go before revealing the answers!

| Q | Question |
|---|----------|
| 1 | What command quickly shows the Windows version and build number? |
| 2 | What is the maximum RAM supported by Windows 11 Enterprise? |
| 3 | Which Windows edition is best suited for large-scale enterprise deployments? |
| 4 | Which edition has the most restricted feature set for everyday home users? |
| 5 | Which security feature is only available on Pro and Enterprise — not Home? |

<details>
<summary>✅ Click to reveal answers</summary>

| Q | Answer |
|---|--------|
| 1 | **`winver`** — launches a dialog showing the version and build number |
| 2 | **6 TB** |
| 3 | **Windows 11 Enterprise** |
| 4 | **Windows 10 Home** |
| 5 | **BitLocker** Drive Encryption |

</details>

---

## 💡 Key Concepts

**Windows Editions at a Glance:**

| Feature | Home | Pro | Enterprise |
|---------|------|-----|-----------|
| BitLocker Drive Encryption | ❌ | ✅ | ✅ |
| Remote Desktop (Host) | ❌ | ✅ | ✅ |
| Group Policy Management | ❌ | ✅ | ✅ |
| Domain Join | ❌ | ✅ | ✅ |
| Max RAM (64-bit) | 128 GB | 2 TB | 6 TB |
| Windows Sandbox | ❌ | ✅ | ✅ |
| Long-Term Servicing Channel | ❌ | ❌ | ✅ |

**How to identify your Windows edition:**
- `Settings → System → About` — shows edition, version, and OS build
- `winver` command — quick popup showing version and build number
- `System Properties` (via Control Panel) — shows edition and activation status

---

## ❓ Knowledge Check — Can You Answer These?

Test yourself before revealing the answers!

| Q | Question |
|---|----------|
| 1 | What command do you run to quickly check the Windows version and build number? |
| 2 | Which Windows editions include BitLocker Drive Encryption? |
| 3 | What is the key difference between Windows 11 Home and Pro for business use? |
| 4 | Where in Settings do you find the Windows edition and OS build number? |
| 5 | Which edition supports the largest maximum RAM? |

<details>
<summary>✅ Click to reveal answers</summary>

| Q | Answer |
|---|--------|
| 1 | **`winver`** — opens a dialog showing version and build |
| 2 | **Pro and Enterprise** — BitLocker is not available on Home editions |
| 3 | Pro supports **domain join, BitLocker, Group Policy, and Remote Desktop hosting** — Home does not |
| 4 | **Settings → System → About** → Windows specifications section |
| 5 | **Windows 11 Enterprise** supports up to **6 TB** of RAM |

</details>

---

## 📁 Repository Structure

```
adegoke-windows-os-editions/
│
├── screenshots/
│   ├── 01_Windows11_Pro_System_About.jpg
│   ├── 02_BitLocker_Search.jpg
│   └── 03_Windows11_Home_Activation.jpg
│
├── lab-report.pdf        ← Original Practice Labs report
├── README.md
└── LICENSE
```

---

## 👤 About This Project

This is a **personal learning project** — part of my ongoing IT and cybersecurity portfolio. Knowing the difference between Windows editions isn't just exam knowledge — it directly affects how you support users, deploy software, and secure devices in a business environment.

📬 **Get in touch:** princeadegokelekan@outlook.com  
🌐 **GitHub:** You're already here!

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.
