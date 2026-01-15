# BNP Paribas Reconnaissance Project

This repository contains the complete reconnaissance project on **BNP Paribas** as part of cybersecurity coursework.  
Only passive information gathering (recon) techniques were used.  
No exploitation or unauthorized access was performed.

---

## 📌 1. Company Homepage Identified
**Main Domain:**  
https://group.bnpparibas.com

![Image](https://github.com/user-attachments/assets/870d3d07-4f5b-468b-bc93-6dc204cb7b76)

---

## 📌 2. Bug Bounty / VDP (HackerOne)
- HackerOne external listing found  
- Domains listed:
  - bnpparibas.com
  - bnppariba.com
  - bnpariba.com

![Image](https://github.com/user-attachments/assets/a515fee4-37e6-4c92-91a1-a1476c9490c7)

---

## 📌 3. Technology Stack (Wappalyzer)

## Technology Stack (Wappalyzer)

**Frontend**
- React
- HeroUI

**JavaScript Libraries**
- jQuery 3.7.1
- Swiper
- LazySizes
- core-js 3.46.0

**Analytics**
- Matomo Analytics
- LinkedIn Insight Tag

**Tag Manager**
- Google Tag Manager

**Security**
- Akamai Bot Manager
- HSTS

**Other**
- Open Graph


![Image](https://github.com/user-attachments/assets/7127536c-e458-4c60-82b1-38244f56d5eb)

---

## 📌 4. Ping Test

Command:
ping bnpparibas.com

Result:
- 0% packet loss  
- Average latency 31 ms  
- IP → 23.220.80.235

![Image](https://github.com/user-attachments/assets/08f2a128-580e-4027-862c-c7c0b7051f46)
---

## 📌 5. Amass Subdomain Enumeration

Command:
amass enum -d bnpparibas.com

Subdomains discovered:
- Multiple A, NS, CNAME records  
- Hosted on Akamai CDN  

![Image](https://github.com/user-attachments/assets/0b4054a6-4859-4dca-814e-a155cbb23c48)

---

## 📌 6. DIG DNS Lookup

Command:
dig bnpparibas.com

Result:
- A record → 23.220.80.235

![Image](https://github.com/user-attachments/assets/1bdd7251-a577-46a7-9fde-481df9e26877)

---

## 📌 7. WHOIS Lookup

Command:
whois 23.220.80.235

Result:
- NetRange: 23.192.0.0/11
- Organization: Akamai Technologies
- ASN: AS20940

![Image](https://github.com/user-attachments/assets/f1c6d9ed-66e8-4ae9-8a5a-5e629e539a7a)

---

## 📌 8. DIRB Scan (Hidden Directories)

Command:
dirb https://bnpparibas.com

Wordlist used:
`common.txt`  

![Image](https://github.com/user-attachments/assets/a679213c-bc20-490d-88f8-575b4dd3298a)


## Conclusion

This recon project shows that BNP Paribas uses a secure and modern infrastructure, Akamai CDN protection, and multiple  
subdomains with strong DNS configuration. Only passive OSINT methods were used, and no exploitation was performed.


## ⚠️ Disclaimer
This project is strictly for educational purposes.  
Only public information gathering methods were used.  
No systems were harmed or accessed illegally.

