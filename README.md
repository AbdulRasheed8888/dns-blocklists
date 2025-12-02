# 🌐 DNS Blocklists  
### Modern, clean, and lightweight blocklists for Pi-hole, AdGuard, and DNS filtering systems.

![Status](https://img.shields.io/badge/status-active-brightgreen?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-blue?style=flat-square)
![DNS Filtering](https://img.shields.io/badge/DNS-filtering-orange?style=flat-square)

---

## 📌 Overview
This repository contains **curated DNS blocklists** designed for:

- **Pi-hole**
- **AdGuard Home**
- **Unbound**
- **dnsmasq**
- **Any DNS filtering system**

The lists are **clean**, **lightweight**, and **focused** — no heavy 500k entries that slow down FTL.  
Only **high-quality domains** verified from real network traffic.

---

## 📁 Available Blocklists

### 🎰 Gambling  
`gambling.txt`  
Blocks betting & casino websites including 1xbet, Melbet, Parimatch, 666d6, and similar networks.

---

### 🔞 Adult Content  
`adult.txt`  
Blocks major adult sites while avoiding false positives.

---

### 🦠 Malware / Phishing  
`malware.txt`  
Blocks malicious, phishing, stealer, RAT, and exploit domains.

---

### 📱 Transsion / Infinix / Tecno Spyware  
`spyware-transsion.txt`  
Blocks background connections from Transsion OS services:
- shalltry.com  
- transsion-os.com  
- allawnos.com  
- bangcdn.net  
…and other hidden telemetry domains.

---

### 📉 Clean Ads & Tracking  
`ads-clean.txt`  
Blocks intrusive ads and trackers **without breaking apps** or Google Play services.

---

## 🚀 Usage (Pi-hole)

### 1️⃣ Add any list
Go to:
```
Pi-hole Admin → Group Management → Adlists → Add
```

### 2️⃣ Use this format:
```
https://raw.githubusercontent.com/<your-username>/dns-blocklists/main/gambling.txt
```

### 3️⃣ Update gravity:
```
pihole -g
```

Done. 🎉

---

## ⚡ Why These Lists?

✔ Based on **real-world DNS traffic**  
✔ Optimized for **performance**  
✔ No duplicate or dead domains  
✔ Updated manually for accuracy  
✔ Avoids breaking apps & services  
✔ Safe for home, school, office & enterprise  

---

## 🛠 Contributions
Feel free to open issues or submit pull requests if you want to add new domains or categories.

---

## 📜 License
This project is licensed under the **MIT License**, meaning you may use, modify, or redistribute the lists freely.

---
