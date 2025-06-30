# 🛡️ OWASP Juice Shop – Security Assessment Report

> ✅ A real-world vulnerability assessment project conducted using OWASP ZAP & Parrot OS as part of the SkillCraft Technology – Future Intern Cybersecurity Internship.

---

## 📌 Project Title
**Vulnerability Assessment of OWASP Juice Shop Web Application**

## 🧑‍🎓 Intern Details
- **Name:** Aman Patel  
- **Track:** Cybersecurity & Ethical Hacking  
- **Program:** Future Intern – Cybersecurity Internship  
- **Conducted by:** *__Future Interns__*

---

## 🧰 Tools & Technologies Used

| Tool             | Purpose                                  |
|------------------|------------------------------------------|
| 🛍️ OWASP Juice Shop | Vulnerable target for assessment         |
| ⚙️ OWASP ZAP        | Active/Passive vulnerability scanning   |
| 🐧 Parrot OS (VM)   | Attacker environment (VirtualBox)       |
| 🌐 Firefox          | Manual testing & browsing               |
| 📝 LibreOffice      | Report writing and documentation        |

---

## 🌍 Test Environment
- **Host OS:** Windows 11  
- **Attacker Machine:** Parrot OS (VirtualBox)  
- **Target:** OWASP Juice Shop (localhost or LAN IP)  
- **Toolchain:** OWASP ZAP, browser proxy configuration

---

## 📄 Report Highlights

- 🔍 5 real-world vulnerabilities discovered
- 📸 Evidence-backed findings with technical details
- 📊 Risk Assessment Table included
- ✅ Recommendations aligned with OWASP Top 10

> 📁 See `README.md` (main) for the full report.  
> 📁 Screenshots and scan evidence are available in the `/screenshots` and `/zap-scan-reports` folders.

---

## 🧪 Vulnerabilities Identified

| No. | Vulnerability                         | Severity | CWE ID  |
|-----|----------------------------------------|----------|---------|
| 1️⃣  | SQL Injection                         | 🔴 High  | CWE-89  |
| 2️⃣  | Cloud Metadata Exposure               | 🟡 Medium| CWE-200 |
| 3️⃣  | Missing Anti-CSRF Tokens              | 🟡 Medium| CWE-352 |
| 4️⃣  | Private IP Disclosure                 | 🟡 Medium| CWE-200 |
| 5️⃣  | Cross-Domain Misconfiguration (CORS)  | 🟡 Medium| CWE-264 |

---

## 📎 Repository Structure
```
📁 owasp-juice-shop-assessment/
│
├── README.md ← Full report (markdown format)
├── screenshots/ ← Screenshots for each vulnerability
├── zap-scan-reports/ ← Optional: ZAP HTML or PDF exports
└── .gitignore / LICENSE ← Optional files
```


---

## 🙏 Acknowledgements

- Special thanks to **Future Interns** for the internship opportunity  
- Appreciation to the **OWASP Foundation** for providing open-source security tools and learning platforms

---

## 🚀 Connect with Me

> 🔗 LinkedIn: [Aman Patel](https://www.linkedin.com/in/its-aman-patel)   
> 🌐 GitHub: [itspatelaman](https://github.com/itspatelaman)

---

### 🔐 *Security is not a destination — it’s a continuous journey.*

