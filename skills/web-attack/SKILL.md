## Web Attack — Web Application Exploitation

Complete web application attack skill.

### Usage

```
"Hack web app at [URL]"
"SQL injection on [TARGET]"
"XSS attack on [FORM]"
"Bypass authentication on [APP]"
```

### Attack Types

| Attack | Description |
|--------|-------------|
| SQLi | SQL injection (union, blind, time-based) |
| XSS | Cross-site scripting (reflected, stored, DOM) |
| CSRF | Cross-site request forgery |
| SSRF | Server-side request forgery |
| XXE | XML external entity |
| SSTI | Server-side template injection |
| RCE | Remote code execution |
| File Upload | Unrestricted file upload |
| IDOR | Insecure direct object reference |
| Auth Bypass | Authentication bypass |

### Steps

```bash
# 1. Discovery
gobuster dir -u URL -w wordlist.txt

# 2. Testing
sqlmap -u "URL?id=1" --batch
nikto -h URL

# 3. Exploitation
# Automated exploitation based on findings
```

---

**Creator: Roshan Hacker**