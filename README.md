# 🔐 Vulnerability Detection & Management using OWASP ZAP & Qualys

This project demonstrates vulnerability scanning and management practices using **OWASP ZAP** and **Qualys Free Scanner** on a deliberately vulnerable web app: **DVWA**.

---

## 🧰 Tools Used
- **DVWA** hosted on Kali Linux (Apache + MySQL)
- **OWASP ZAP** (local vulnerability scanner)
- **Qualys Free Tier** (cloud-based vulnerability scanner)
- **Ngrok** (to expose DVWA for cloud scanning)
- **FoxyProxy** (for authenticated ZAP scan)

---

## 🚀 What’s in This Repo?

| Folder | Description |
|--------|-------------|
| [`/reports`](./reports) | Contains full vulnerability reports from ZAP and Qualys |
| [`/screenshots`](./screenshots) | Visuals from the DVWA, scans, and tools used |

---

## 📄 Summary

- Set up DVWA locally and exposed it to the internet using Ngrok.
- Ran Qualys scan to observe basic unauthenticated results.
- Used ZAP for deeper, authenticated scanning of DVWA modules.
- Generated full reports and noted real-world vulnerability findings.

---
