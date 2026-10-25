# 🦉 OAnonFtp

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-0a0c10?style=flat-square"/>
  <img src="https://img.shields.io/badge/Category-OAttack%20/%20Offensive-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-1.0.0-cyan?style=flat-square"/>
</p>

> **OAnonFtp** — Authorised anonymous FTP audit and read-only access card

---

> ⚠️ **AUTHORISED USE ONLY** — Use only on systems you own or have explicit written permission to test. Unauthorised use is illegal.

---

## 📌 Overview

OAnonFtp performs an authorised, read-only audit of a single FTP server for anonymous access. It tries only a known set of anonymous accounts and passwords and never uploads, deletes or guesses credentials outside that anonymous set. On success it records a read-only access card capturing the server banner, system type and advertised features for your report.

---

## ✨ Features

- Checks one host for anonymous FTP access using a fixed anonymous credential set
- Strictly read-only: never uploads, deletes or brute-forces passwords
- Records an access card with banner, system type and feature list
- Configurable FTP port with range validation
- Results stored under an XDG data directory with restricted permissions
- Simple GUI plus non-interactive --check mode for scripting

---

## ⚙️ Requirements

- **Linux**
- **No Python installation needed** — runs as a standalone executable

---

## 🚀 Usage

```bash
./OAnonFtp --check 192.168.1.10
./OAnonFtp --check ftp.example.com --port 2121
./OAnonFtp --help
```

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 300+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

MIT License — © Khaled S. Haddad

*Tools are distributed as pre-built executables. Source code is proprietary.*
