# Web-application-security

# Web Application and Network Security Projects

This repository contains two projects focused on securing web applications and network communications. These projects explore SSL/TLS for secure connections and HTTP cookies for session management.

### **1. Secure Session Establishment with SSL/TLS**
- Analyze the SSL/TLS handshake (`ClientHello`, `ServerHello`, certificate exchange, key exchange).
- Ensure confidentiality, integrity, and authenticity in data transmission.
- Tools: Wireshark for traffic capture and analysis.

### **2. Session Persistence with Cookies in HTTP**
- Understood how `Set-Cookie` and `Cookie` headers manage session states.
- Analyze HTTP traffic to observe cookie exchanges.
- Tools: Wireshark for analyzing session persistence.

---

## **Deliverables**
- Reports explaining each project's findings.
- Wireshark packet captures with annotations.

---

# Web Application Security Projects

## 1. Basic Interception with Burp Suite

### Objective:
Learn to intercept and modify web traffic using Burp Suite.

### Setup:
1. **Install Burp Suite** from [here](https://portswigger.net/burp/communitydownload).
2. **Set up a browser** (Firefox or Chrome) to use Burp Suite as a proxy.
3. **Install Burp’s CA certificate** to intercept HTTPS traffic.

### Steps:
1. Open a website and let Burp Suite intercept the traffic.
2. Change a request (e.g., modify the User-Agent).
3. Send the modified request and observe the response.
4. Took screenshots of the changes.

---

## 2. Performing a Simple Web Application Scan

### Objective:
Scan a vulnerable web app for security issues with Burp Suite.

### Setup:
1. **Installed Burp Suite**.
2. **Set up a vulnerable web app** (e.g., Juice Shop or DVWA).
3. **Configure Burp Suite** as a proxy.

### Steps:
1. Let Burp Suite crawl the web app.
2. Run a security scan using Burp Suite.
3. Checked for vulnerabilities (e.g., SQL injection, XSS).
4. Noted the findings and possible fixes.

---

### Conclusion:
These labs teached how to use Burp Suite for security testing. And Always use local or vulnerable sites for testing.





