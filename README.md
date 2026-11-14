# Week 2 – Project Module 1: Footprinting & Reconnaissance Using Kali Linux

## 📌 Project Overview

This project focuses on **Footprinting and Reconnaissance**, the initial phase of ethical hacking and cybersecurity assessments.

The objective is to gather publicly available information about a target domain using multiple built-in Kali Linux tools. This helps understand domain registration details, DNS records, web technologies, HTTP headers, and Web Application Firewall (WAF) protection.

**Target Domain:** `networkwalks.com`

**Environment:** Kali Linux

## 🎯 Objectives

- Understand the fundamentals of footprinting and reconnaissance.
- Gather domain registration information.
- Identify website technologies and services.
- Resolve domain names into IP addresses.
- Analyze HTTP response headers.
- Detect Web Application Firewall (WAF).
- Enumerate DNS records.

## 🛠️ Tools Used

| Tool | Purpose |
|---|---|
| WHOIS | Domain registration information |
| WhatWeb | Website technology fingerprinting |
| Nslookup | DNS lookup and IP resolution |
| cURL | HTTP response header analysis |
| WAFW00F | Web Application Firewall detection |
| DNSRecon | DNS enumeration |

## 🔍 Tasks Performed

### Task 1: WHOIS – Domain Information
```bash
whois networkwalks.com
```
Collected publicly available domain registration details, registrar information, registration dates, and name servers.

### Task 2: WhatWeb – Technology Fingerprinting
```bash
whatweb networkwalks.com
```
Identified website technologies, web server information, CMS, and other publicly exposed details.

### Task 3: Nslookup – DNS Resolution
```bash
nslookup networkwalks.com
```
Resolved the domain name into its corresponding IP address using DNS.

### Task 4: cURL – HTTP Header Analysis
```bash
curl -I https://networkwalks.com
```
Examined HTTP response headers, server information, status codes, and redirect details.

### Task 5: WAFW00F – Firewall Detection
```bash
wafw00f networkwalks.com
```
Identified whether a Web Application Firewall was protecting the target website.

### Task 6: DNSRecon – DNS Enumeration
```bash
dnsrecon -d networkwalks.com
```
Enumerated DNS records, including name servers, mail servers, TXT records, SPF information, and service records.

## 📚 Key Learnings

- Understanding passive reconnaissance techniques.
- Learning how to collect publicly available information.
- Understanding DNS resolution and domain infrastructure.
- Identifying website technologies and server information.
- Understanding HTTP response headers.
- Learning the importance of WAF detection.
- Understanding how reconnaissance supports vulnerability assessment.

## 📸 Project Screenshots

This folder contains screenshots of the practical tasks performed using Kali Linux.

- WHOIS output
- WhatWeb output
- Nslookup results
- cURL HTTP headers
- WAFW00F results
- DNSRecon output

## 🧠 Conclusion

Successfully completed the Week 2 Project Module 1 on Footprinting and Reconnaissance using multiple Kali Linux tools.

This hands-on project improved my understanding of information gathering, DNS enumeration, website fingerprinting, and network reconnaissance.

It also helped me understand how attackers collect information and how cybersecurity professionals can use the same techniques to identify and reduce publicly exposed information.

## ⚠️ Disclaimer

This project is strictly for educational and ethical cybersecurity learning purposes.

All practical activities should be performed only on systems you own or have explicit permission to assess. Unauthorized scanning or testing is prohibited.

---

**Learning Journey:** Cybersecurity & Ethical Hacking  
**Platform:** Kali Linux  
**Project:** Week 2 – Project Module 1
