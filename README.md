<div align="center">

# 🦉 OAnonFTP

**FTP Anonymous & Weak Login Scanner**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

*Part of the [OwlSec](https://owlsec.org) Toolkit*

</div>

---

## 📌 Overview

**OAnonFTP** is an FTP security auditing tool that checks for anonymous access and weak login credentials on FTP servers. Designed for authorized penetration testing and educational purposes.

---

## 🖥️ Interface

| Field | Description |
|-------|-------------|
| **TARGET** | IP address or Hostname of the FTP server |
| **PORT** | FTP port — default is `21`, change if needed |
| **START SCAN** | Begin scanning for anonymous or weak logins |
| **LIST FILESYSTEM** | Browse the FTP filesystem (enabled on success) |

---

## 🚀 Usage
```bash
./OAnonFTP
```

1. Enter the **Target IP** or Hostname
2. Set the **Port** (default: 21)
3. Click **START SCAN**
4. If access is found, use **LIST FILESYSTEM** to explore

---

## ⚙️ Requirements

- Linux (any distro)
- The tool is pre-built — no Python installation needed

---

## ⚠️ Legal Disclaimer

> **THIS TOOL IS FOR EDUCATIONAL AND AUTHORIZED AUDIT PURPOSES ONLY.**
> Unauthorized access to systems is illegal.
> The developer is not responsible for any misuse.

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 300+ security and privacy tools.

> 🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

MIT License — © Khaled S. Haddad

*Tools are distributed as pre-built executables. Source code is proprietary.*
