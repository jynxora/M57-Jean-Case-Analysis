# 🕵️‍♂️ M57-Jean Case: A Complete Digital Forensics Walkthrough (Autopsy-based)

> **Case Type**: Insider Threat · Browser Exploits · Remote Access Abuse · Anti-Forensics  
> **Skill Level**: Beginner-to-Intermediate (DFIR)  
> **Investigation Time**: 36-37 Hours

---

## About the Case

The **M57 Jean Case** is a fictional but realistic forensic challenge created by **NIST** [National Institute of Standards and Technology] to simulate an insider threat scenario. A confidential spreadsheet containing salary and identity data was leaked from the laptop of Jean — a senior executive at M57.Biz.  

Jean denies any wrongdoing, claiming her system must’ve been compromised. As forensic analysts, our goal is to determine whether Jean is telling the truth — or if something more malicious happened under the hood.

---

## What This Repository Achieves

This repo contains a **complete, self-driven digital forensic analysis** of Jean's system using the Autopsy toolset.  
You'll walk through:

- How browser-based phishing leads to system compromise  
- How to identify and verify signs of **Remote Assistance abuse**  
- Detection of **session hijacking**, **JavaScript surveillance**, and **cached HTML payloads**  
- Tracing **deleted binaries**, **anti-forensic activities**, and installation of suspicious software (e.g., AIM6 toolbars)  
- Learning **which artifacts matter** — and which are red herrings (decoys)

This investigation emphasizes **evidence interpretation**, **timeline building**, and **investigative discipline** — not just tool usage.

---

## Who This Is For

This repo is built for:

- **DFIR learners and students**  
- **Cybersecurity enthusiasts and CTF players**  
- **Autopsy users seeking real-case practice**  
- **Anyone exploring Windows XP era forensic artifacts**  

You’ll find not only the technical findings, but also the **thought process**, **pitfalls**, and **honest reflection** on what I missed.

---

Read the Write-up

1. 🔍 **Read the full report (PDF) in-browser**  
   [Read PDF Report](M57-Jean_Autopsy_Case_Analysis.pdf)

2. 📝 **Read the full report (Markdown) in-browser**  
   [Read .Markdown Report](./Markdown%20Report/M57-Jean_Autopsy_Case_Analysis.md)

3. ⬇️ **Download the full PDF directly**  
   [Download PDF Report](https://github.com/jynxora/M57-Jean-Case-Analysis/raw/main/M57-Jean_Autopsy_Case_Analysis.pdf)

---

## 🔦 What You’ll Learn

- How forensic data is spread across browser caches, logs, temp folders, and system files
- How to detect privilege escalation and remote access abuse from system clues
- Why some artifacts (like `.bmp` images or `readme.txt` files) are **deliberate noise**
- How to think critically and avoid rabbit holes in real forensic investigations

---

## Contribute or Fork

If you’re analyzing the M57 dataset yourself:
- Fork this repo and expand the timeline
- Add your own findings under `/notes/`
- Submit issues if you spot artifacts I missed!

---

## Author Info

**Jinay Shah** (aka `Jynx`)  
🔗 [LinkedIn](https://linkedin.com/in/jynxora) · [X](https://x.com/JynxZero) · [Medium](https://medium.com/@jynxora)

---

## ⭐ Bonus: Key Takeaway

> Not every file is evidence. Not every clue matters.  
> DFIR isn’t just about finding things — it’s about **telling the right story with the right artifacts**.
