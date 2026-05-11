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

# 👨‍💻 Author

Jaga — VAPT Learner & Security Research Enthusiast
