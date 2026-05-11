# 🔥 Vulnerable Web Application Lab

A deliberately vulnerable web application built using Flask for VAPT, bug bounty, and web security learning purposes.

This project contains intentionally insecure implementations of common web vulnerabilities for educational and testing environments only.

---

# 🚀 Features

- SQL Injection
- Cross-Site Scripting (XSS)
- IDOR (Insecure Direct Object Reference)
- Command Injection
- File Upload Vulnerability
- Weak Session Management
- Cookie Tampering
- Flask Debug Mode

---

# 🛠️ Tech Stack

- Python 3
- Flask
- SQLite
- HTML
- Kali Linux

---

# 📂 Project Structure

```bash
vulnerable-lab/
├── app.py
├── templates/
├── static/
├── uploads/
├── screenshots/
├── docs/
└── README.md
```

---

# ⚙️ Installation

## Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/vulnerable-lab.git

cd vulnerable-lab
```

## Create Virtual Environment

```bash
python3 -m venv venv
source venv/bin/activate
```

## Install Dependencies

```bash
pip install -r requirements.txt
```

## Run Application

```bash
python app.py
```

Open:

```bash
http://127.0.0.1:5000
```

---

# 🧪 Vulnerability Labs

| Vulnerability | Route |
|---|---|
| SQL Injection | /login |
| XSS | /xss |
| IDOR | /idor |
| Command Injection | /cmd |
| File Upload | /upload |
| Cookie Tampering | /cookie |

---

# 📸 Screenshots

## Home Page

![Home](screenshots/home.png)

---

## SQL Injection

![SQLi](screenshots/sql-login.png)

---

## XSS

![XSS](screenshots/xss.png)

---

## Command Injection

![CMD](screenshots/cmd.png)

---

## File Upload

![Upload](screenshots/upload.png)

---

## Cookie Tampering

![Cookie](screenshots/cookie.png)

---

# 🔐 Example Payloads

## SQL Injection

```sql
admin' OR '1'='1
```

## XSS

```html
<script>alert('XSS')</script>
```

## Command Injection

```bash
127.0.0.1; whoami
```

---

# ⚠️ Disclaimer

This project is intentionally vulnerable and must only be used:

- In local environments
- For educational purposes
- For legal security testing

Do NOT deploy publicly.

---

# 📚 Learning Objectives

- Understand common web vulnerabilities
- Practice VAPT techniques
- Learn manual testing
- Use Burp Suite & OWASP methodologies
- Build exploit development skills

---

# 🧰 Recommended Tools

- Burp Suite
- OWASP ZAP
- sqlmap
- ffuf
- flask-unsign

---

# 👨‍💻 Author

Developed by Jaga for VAPT practice and security research.
.gitignore
          venv/
__pycache__/
*.pyc
database.db
uploads/
.env
