
# Secure Cloud Web Hosting & Vulnerability Assessment

This project demonstrates an end-to-end deployment and security validation workflow, combining cloud infrastructure (AWS S3 & EC2) with cybersecurity best practices (server hardening and vulnerability scanning).

---

## Project Overview

- **Goal**: Deploy a static website on AWS S3, harden an Ubuntu EC2 instance, and perform vulnerability assessments using Nmap and Nikto.
- **Skills showcased**: AWS S3 static hosting, EC2 provisioning, Linux hardening (UFW, Fail2Ban, SSH configuration, automatic updates), port scanning, web vulnerability scanning, documentation.

---

## Repository Structure

```
secure-cloud-project/
├── README.md              # This file
├── website/               # Static site files
│   ├── index.html
│   └── style.css
├── screenshots/           # Proof-of-work images
│   ├── snapshot1.PNG      # S3 bucket created
│   ├── snapshot2.PNG      # Files uploaded
│   ├── snapshot3.PNG      # Static website enabled
│   ├── snapshot4.PNG      # Bucket policy applied
│   ├── snapshot5.PNG      # Website opened in browser
│   ├── snapshot6.PNG      # EC2 instance launched
│   ├── snapshot7.PNG      # SSH into VM
│   ├── snapshot8.PNG      # UFW firewall status
│   ├── snapshot9.PNG     # SSH hardening config
│   ├── snapshot10.PNG     # Automatic updates
│   ├── snapshot11.PNG     # Nmap scan result
│   └── snapshot12.PNG     # Nikto S3 scan result
```

---

## Summary of Work

###  Static Website on AWS S3
- Uploaded `index.html` and `style.css` to S3 bucket.
- Enabled static website hosting.
- Made the site public with a bucket policy.
- Verified live access via browser.

###  EC2 Linux VM Hardening
- Launched Ubuntu EC2 instance.
- Secured SSH: `PermitRootLogin no`, `PasswordAuthentication no`.
- Enabled UFW and Fail2Ban.
- Configured automatic updates.

### Vulnerability Assessment
- **Nmap**: Scanned EC2 public IP for open ports and services.
- **Nikto**: Scanned S3 static site for web vulnerabilities.

---

## Screenshots

Each major step is backed with a snapshot in the `/screenshots` folder.

---

##  Conclusion

- Demonstrated knowledge of AWS S3, EC2, Linux security practices, and vulnerability testing.
- Ideal project for showcasing cloud + cybersecurity fundamentals.

---

MIT © 2025 Joseph
