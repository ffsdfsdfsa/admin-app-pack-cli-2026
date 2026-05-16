# 🛠️ Admin App Pack CLI

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python)
![Platform](https://img.shields.io/badge/OS-macOS%20%7C%20Linux-lightgrey?style=for-the-badge&logo=apple)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

**Admin App Pack CLI** is a multitool for system administrators, information security specialists, and developers. The project brings together a set of lightweight, independent command-line utilities for automating routine tasks, network operations, and secure data generation.

---

## 📸 Interface Screenshot

![App Main Menu](https://via.placeholder.com/800x400.png?text=A+beautiful+screenshot+of+your+terminal+goes+here)

---

## ✨ Key Features

The package features a modular system of mini-applications (Apps). Currently implemented:

* 🔐 **Secure Account Generator**
  Generates cryptographically strong passwords. The core feature is the **structural separation of credentials**. The script outputs a separate `password` for email access and a distinct `pp_password` for the service itself. This prevents a complete data breach if one node is compromised.
* 🌐 **Network Scanner (Port Checker)**
  A utility for quickly checking TCP port availability on remote hosts (e.g., a quick ping of port 22 before establishing an SSH connection to a remote server).
* 🧩 **Modular Architecture**
  Adding a new utility takes just a couple of minutes by simply dropping a new `.py` file into the `apps/` directory.

---

## 🚀 Installation and Setup

The project relies purely on standard Python libraries and does not require heavy third-party dependencies. It works perfectly in a standard macOS terminal or any Unix system.

### 1. Clone the repository
Download the project to your local machine:
```bash
git clone (https://github.com/ffsdfsdfsa/admin-app-pack-cli-2026)](https://github.com/YOUR_USERNAME/admin-app-pack-cli.git)
cd admin-app-pack-cli
