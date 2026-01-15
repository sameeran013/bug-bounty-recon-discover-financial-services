📌 Project Title

Bug Bounty Reconnaissance – Discover Financial Services
# Bug Bounty Reconnaissance – Discover Financial Services

## 📌 Project Overview
This project focuses on reconnaissance techniques used in bug bounty programs, targeting **Discover Financial Services** for educational and academic purposes only. The objective is to understand how organizations define scope, protect assets, and maintain strong security postures through reconnaissance-level analysis.

No exploitation or unauthorized access was performed during this project.

---

## 🏢 Target Organization
- **Company Name:** Discover Financial Services  
- **Main Domain:** discover.com  

The domain was verified through official website pages and public records.

---

## 🔍 Reconnaissance Activities Performed

### 1️⃣ Main Domain Identification
- Verified official domain using search engines and homepage validation.

### 2️⃣ Bug Bounty / Vulnerability Disclosure
- Discover maintains an official vulnerability disclosure program, typically hosted on platforms like **HackerOne**.
- Search keywords used:
  - Discover bug bounty
  - Discover vulnerability disclosure

### 3️⃣ Scope Identification
**In-Scope Assets**
- discover.com
- Discover-owned subdomains
- Official web applications and services

**Out-of-Scope Assets**
- Third-party services
- Customer-controlled accounts
- Social media platforms

---

### 4️⃣ ICMP Ping Test
- **Command Used:**  
ping discover.com
- **Observation:**  
ICMP requests are blocked, indicating strong security controls.

---

### 5️⃣ Technology Stack Identification
- **Tool Used:** Wappalyzer  
- **Technologies Identified Include:**
- Web server
- CDN
- JavaScript frameworks
- Analytics and security tools

---

### 6️⃣ ASN and IP Range Identification
- **Commands Used:**
dig discover.com
whois <IP_ADDRESS>
- **Information Collected:**
- ASN Number
- Organization / ISP
- Network ranges

---

### 7️⃣ Subdomain Enumeration
- **Tool Used:** Amass  
- **Command:**
amass enum -d discover.com
- **Purpose:**  
To identify publicly accessible subdomains.

---

### 8️⃣ Subdomain Technology Analysis
**Subdomains Analyzed:**
- www.discover.com
- portal.discover.com
- jobs.discover.com
- apply.discover.com
- secure.discover.com

Each subdomain was analyzed using Wappalyzer to compare technology stacks.

---

### 9️⃣ Hidden Files & Directory Enumeration
⚠️ Scanned only the main domain

- **Tool Used:** Dirb  
- **Command:**
dirb https://www.discover.com
- **Observation:**  
Minimal directory exposure, indicating robust security measures.

---

## ⚠️ Disclaimer
This project was conducted **strictly for educational purposes**.

- No exploitation was performed
- No brute-force attacks were used
- All activities followed ethical hacking principles
- Reconnaissance was performed within publicly accessible boundaries

This project complies with Discover’s vulnerability disclosure policy and academic guidelines.

---

## 👤 Author
**Sameeran Surin**  
ERP: 6605912  

---

## 📚 Tools Used
- Ping
- Wappalyzer
- Dig
- Whois
- Amass
- Dirb

---

## ⭐ Acknowledgement
Thanks to Discover Financial Services for maintaining transparent security policies and to the academic institution for providing guidance on ethical cybersecurity practices.
