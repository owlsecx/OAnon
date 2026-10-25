# 🦉 OAnon

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-0a0c10?style=flat-square"/>
  <img src="https://img.shields.io/badge/Category-OCore-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-1.0.0-cyan?style=flat-square"/>
</p>

> **OAnon** — anonymous and secure internet browsing

---

> ⚠️ **AUTHORISED USE ONLY** — Use only on systems you own or have explicit written permission to test. Unauthorised use is illegal.

---

## 📌 Overview

OAnon is a privacy and anonymity control center that manages a dedicated Tor instance for anonymous, compartmentalised browsing. It runs its own Tor SOCKS and control ports so it never conflicts with a system Tor service and does not require elevated privileges to start or stop. A graphical interface shows live connection state and verifies the exit identity through multiple geo-IP APIs.

---

## ✨ Features

- Dedicated Tor instance on isolated SOCKS/control ports (no system-Tor conflict)
- Start/stop anonymous browsing without root privileges
- Exit-IP verification via check.torproject.org and multiple geo-IP APIs
- Isolated browser profile and Tor data directory under /tmp
- Live connection status and country/ISP display in a GUI
- OWL-themed dark interface for quick monitoring

---

## ⚙️ Requirements

- **Linux**
- **No Python installation needed** — runs as a standalone executable

---

## 🚀 Usage

```bash
./OAnon
./OAnon --help
```

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 300+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

MIT License — © Khaled S. Haddad

*Tools are distributed as pre-built executables. Source code is proprietary.*
