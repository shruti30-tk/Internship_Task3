# Internship_Task3
# Task 3: Vulnerability Scan Using Nessus on Windows

- Objective: Use free tools to identify common vulnerabilities on your computer.
- Tools: OpenVAS Community Edition (free vulnerability scanner) or Nessus Essentials.
- Deliverables: Vulnerability scan report with identified issues.

---

## Tools Used

- **Nessus Essentials** – Free vulnerability scanner by Tenable
- **Operating System** – Windows 10 (or your version)
- **Browser** – Used to access Nessus web interface

---

## Steps Performed

1. **Registered for Nessus Essentials** on Tenable’s official website and received an activation key.
2. **Installed Nessus on Windows** and completed initial setup at `https://localhost:8834`.
3. **Created a Basic Network Scan** with the target set to `127.0.0.1` (localhost).
4. **Launched the scan**, which took ~30–40 minutes.
5. **Reviewed the scan report**, focusing on high and critical vulnerabilities.
6. **Captured screenshots** and noted CVE IDs for key findings.
   [Task 3](https://github.com/user-attachments/assets/838d630b-e4d9-45fd-8e06-d6f0fcf85959)
[Task 3 2](https://github.com/user-attachments/assets/93ef445c-5544-4038-bc4e-13a04ec8ee03)
[Screenshot 2025-06-26 164846](https://github.com/user-attachments/assets/e21e8d2f-6b5d-4fa2-af56-d5a3ba1cff87)



## Scan Summary

> Medium issue - SSL/TLS Weak Ciphers               
> Medium issue - SMB Signing not required 
> Low- Informational Findings  

---

## Remediation Highlights

- **Disabled SMBv1** via Control Panel → Windows Features.
- **Updated outdated software** to the latest secure versions.
- **Planned** to harden TLS settings via registry if needed.

---

## Key Learnings

- Gained hands-on experience with automated vulnerability scanning.
- Understood the difference between **vulnerability scanning** and **penetration testing**.
- Learned how to read vulnerability details, including CVSS score, CVE ID, and plugin information.
- Recognized the importance of regular scans for personal system hygiene.

---

> This task gave me a solid foundation in identifying and addressing common security risks using industry tools.
