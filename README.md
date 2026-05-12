# 🔥 Vulnerable Flask Web Application Lab

A deliberately vulnerable Flask web application created for:

- VAPT Practice
- Bug Bounty Training
- OWASP Learning
- Web Exploitation Practice

---

# 🚀 Features

## Vulnerabilities Included

- SQL Injection
- Cross Site Scripting (XSS)
- IDOR
- Command Injection
- File Upload Vulnerability
- Weak Flask Session Management

---

# 🛠️ Technologies

- Python 3
- Flask
- HTML/CSS
- Kali Linux

---

# 📂 Project Structure

```bash
vulnerable-lab/
│
├── app.py
├── requirements.txt
├── README.md
├── .gitignore
│
├── templates/
│   ├── index.html
│   ├── login.html
│   ├── xss.html
│   ├── cmd.html
│   ├── upload.html
│   ├── idor.html
│   └── cookie.html
│
├── screenshots/
│
└── uploads/
```

---

# ⚙️ Installation

## Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/vulnerable-lab.git

cd vulnerable-lab
```

---

## Create Virtual Environment

```bash
python3 -m venv venv

source venv/bin/activate
```

---

## Install Requirements

```bash
pip install -r requirements.txt
```

---

## Run Application

```bash
python app.py
```

Open:

```bash
http://127.0.0.1:5000
```

---

# 🧪 Vulnerability Routes

| Vulnerability | Endpoint |
|---|---|
| SQL Injection | /login |
| XSS | /xss |
| IDOR | /idor |
| Command Injection | /cmd |
| File Upload | /upload |
| Cookie Tampering | /cookie |

---

# 🔐 Example Payloads

## SQL Injection

```sql
admin' OR '1'='1
```

---

## XSS

```html
<script>alert('XSS')</script>
```

---

## Command Injection

```bash
127.0.0.1; whoami
```

---

# 📸 Screenshots

Add screenshots inside:

```bash
screenshots/
```

Example:

- home.png
- xss.png
- sqli.png
- cmd.png

---

# ⚠️ Disclaimer

This project is intentionally vulnerable and must ONLY be used for:

- Educational purposes
- Local testing
- Authorized environments

DO NOT deploy publicly.

---
📊 Vulnerability Coverage

    OWASP Top 10	Coverage	Difficulty Levels
A1: Injection	SQLi, Command Inj	Low/Med/High/Impossible
A3: XSS	Reflected, Stored, DOM	4 Levels
A5: Security Misconfig	File Upload RCE	Unrestricted
A7: XSSI/CSRF	Token Bypass	Multiple Vectors
A10: LFI/RFI	Path Traversal	Absolute/Relative

Total Challenges: 25+ | Score Tracking: Yes | Hints: Per Challenge

 Challenges: Login: admin / password | Guest mode available
🎯 Supported Attack Vectors
Vulnerability	Payload Examples	Tools
SQL Injection	' OR 1=1--, UNION SELECT, Blind Tautology	sqlmap, Burp
XSS	<script>alert(1)</script>, javascript:alert(), DOM	XSStrike, dalfox
File Upload	shell.php, ..%2f, MIME Bypass	Burp, file inclusion
Command Injection	; ls, && whoami, | nc, PowerShell	Commix
LFI/RFI	../../../etc/passwd, PHP wrappers, TFTP	gf lfi, LFI payloads
CSRF	Missing tokens, GET actions	CSRF PoC generator

   Burp Suite Community Workflow:

text
1. Proxy → Target → Scope
2. Spider → Map app
3. Repeater → Test payloads
4. Intruder → Fuzz parameters
5. Scanner → Auto-detect


   🏆 Training Roadmap

text
Week 1:  SQLi + XSS (Low/Medium) → Burp basics
Week 2:  File Upload + LFI → Custom payloads  
Week 3:  Command Inj + Auth → Automation
Week 4:  High/Impossible → Bypass techniques
Week 5:  CTF + Report writing

Cert Prep: eJPT, eWPT, OSCP, Burp Certified


🐛 Troubleshooting
 
Issue	Fix
500 Error	sudo chmod -R 755 storage/
DB Connection	Check .env creds
XSS Blocked	Switch security level
Upload Fails	Disable mod_security
Slow Performance	docker stats + increase RAM

Logs: docker logs vulnweblab


  🤝 Contributing

text
1. Fork → Clone → Branch (feature/add-sqli-timebased)
2. Add vulnerability → Test all levels
3. Write payloads → Update docs
4. PR with writeup → 🎉

👨‍💻 Author

Jagadish A
Web Application Penetration Tester | Bug Bounty Hunter | Security Trainer
🌐 Portfolio	📧 Contact	💼 LinkedIn	🐦 X/Twitter
jagadish-prof.netlify.app	ajagadish0987@gmail.com	in/jagadish-a	@jagadish_sec

Special Thanks: OWASP, PortSwigger, sqlmap team



  



       

