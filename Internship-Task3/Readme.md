# 🔍 Basic Vulnerability Scanning Task (Internship)

This task was focused on learning and performing basic vulnerability scanning using **Tenable Nessus Essentials** as part of my cybersecurity internship.

---

## 📚 Understanding Nessus

Before starting the scans, I spent time understanding:

- **What Nessus is** – It is a powerful vulnerability scanning tool used by professionals.
- **How it works** – Learned through YouTube videos and from google.
- **Why it's important** – It helps us to identify misconfigurations, outdated software, and known vulnerabilities on systems and also provides its solutions.

---

## 🛠️ Setup Process

- Installed **Nessus Essentials** on my local machine.
- Activated it with a free license key from Tenable.
- Completed initial setup and plugin download.
- Explored the dashboard and scan types available.
- I done this all with help of you tube video and those steps are also provided in TryHackMe Lab.

---

## 🖥️ Scanning Targets

I scanned **two hosts** on my network:

1. **My Own PC** – A Windows system, fully updated.
2. **Metasploitable2 VM** – A vulnerable virtual machine for testing.

---

## 🔎 Scan Procedure

- First of all I performed **Host Discovery** using Nessus to identify live devices on the network.
- Selected the identified IP addresses of my PC and the Metasploitable VM.
- Used the **Basic Network Scan** template to perform full scans.
- Focused on identifying:
  - Open ports
  - Running services
  - Known CVEs
  - Vulnerable software and configurations

---

## 📊 Reports & Results

- **My PC**:
  - No high-risk vulnerabilities were found.
  - System is secure and well-patched.

- **Metasploitable2**:
  - Multiple critical vulnerabilities discovered.
  - Services like Apache, Samba, vsFTPd, and MySQL were outdated and exploitable.
  - I have also provided the reports generated for both scans.

---

## 🧪 Additional Learning

To strengthen my understanding of Nessus and vulnerability scanning, I also:

- **Solved a TryHackMe room focused on Nessus**.
  - Learned practical scanning techniques.
  - Understood how to interpret scan results in a lab setting.
  - Practiced identifying common misconfigurations.
  - 🔗 [TryHackMe – Nessus Room](https://tryhackme.com/room/rpnessusredux)

---

## 📌 Included Materials

- ✅ Vulnerability Scan Report – Metasploitable2 (PDF)
- ✅ Screenshots of Nessus dashboard and scans
- ✅ This README file

---

## ✅ Conclusion

This task gave me hands-on experience with real-world tools used in vulnerability assessment. I learned the full lifecycle — from setting up Nessus to scanning, analyzing results, and identifying critical risks. Solving the TryHackMe room also helped reinforce these concepts practically.

I also saw the video of OpenVAS community edition tool but I thought it was a bit difficult to setup so for now I done everything with help of Nessus only.

