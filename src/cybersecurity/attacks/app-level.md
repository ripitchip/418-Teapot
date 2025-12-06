# **Application‑Level Attacks**

Application‑level attacks target the software layer — websites, APIs, mobile apps, and backend services — exploiting flaws in logic, authentication, or input handling.

---

# **Common Application‑Level Attack Types**

### **1. SQL Injection (SQLi)**

Attackers inject malicious SQL queries to read, modify, or delete database data.

### **2. Cross‑Site Scripting (XSS)**

Malicious scripts are injected into web pages, allowing attackers to steal cookies, session tokens, or perform actions as the victim.

### **3. Cross‑Site Request Forgery (CSRF)**

Tricks a user’s browser into performing unintended actions (e.g., changing passwords, sending money).

### **4. Remote Code Execution (RCE)**

Exploitation that allows an attacker to run arbitrary code on the target server.

### **5. Insecure Deserialization**

Tampered serialized objects lead to privilege escalation or code execution.

### **6. Directory Traversal**

Attackers access files outside the intended web directory using path manipulation (`../`).

### **7. Server‑Side Request Forgery (SSRF)**

The application is tricked into making network requests, often accessing internal systems.

### **8. Authentication & Session Attacks**

Weak session tokens, stolen cookies, or flawed login logic allow unauthorized access.

---

# **Major Real‑World Application Attacks (Top 5)**

### **1. Equifax Breach (2017)**

A vulnerability in Apache Struts led to massive data exposure (SSNs, birthdates, etc.).

### **2. Log4Shell (2021)**

A simple logging string triggered remote code execution in millions of Java applications.

### **3. Heartbleed (2014)**

OpenSSL bug allowed attackers to read memory, exposing passwords and private keys.

### **4. Uber API Breach (2016)**

Hard‑coded credentials in source code let attackers access customer/driver data.

### **5. WordPress Plugin Vulnerabilities (Ongoing)**

Thousands of sites compromised yearly due to insecure or outdated plugins.

---

# **Common Tools Used in App‑Level Attacks**

* **Burp Suite** – Proxy for intercepting and modifying web traffic
* **OWASP ZAP** – Open‑source web app scanner
* **sqlmap** – Automated SQL injection tool
* **DirBuster / gobuster** – Directory and file enumeration
* **Metasploit** – Framework for exploiting known vulnerabilities
* **Postman / curl** – API testing and fuzzing