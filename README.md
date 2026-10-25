# 🦉 OVigilant

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-0a0c10?style=flat-square"/>
  <img src="https://img.shields.io/badge/Category-OForensics-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-1.0.0-cyan?style=flat-square"/>
</p>

> **OVigilant** — Host security audit scanner across system, network, ports, users, processes and services

---

> ⚠️ **AUTHORISED USE ONLY** — Use only on systems you own or have explicit written permission to test. Unauthorised use is illegal.

---

## 📌 Overview


OVigilant is a continuous host and service monitoring tool that watches for changes in processes, ports, files and system state and raises alerts on anomalies. It takes periodic snapshots, diffs them against a baseline, and reports deviations for defensive awareness. It is intended for authorized endpoint and infrastructure monitoring.

---

## ✨ Features


- Periodic snapshots of processes, listening ports, files and system state
- Baseline diffing to surface new, removed or changed items
- Anomaly alerting on unexpected deviations
- Configurable monitoring interval and watched resources
- Structured log/export output for review and SIEM ingestion
- Offline --self-test for safe verification

---

## ⚙️ Requirements

- **Linux**
- **No Python installation needed** — runs as a standalone executable

---

## 🚀 Usage


```bash
./OVigilant
./OVigilant --self-test
./OVigilant --help
```

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 300+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

MIT License — © Khaled S. Haddad

*Tools are distributed as pre-built executables. Source code is proprietary.*
