<p align="center">
  <img src="https://raw.githubusercontent.com/TEAMBCS/Web-Analyzer/main/Logo%20and%20Screenshot/Web_Analyzer_logo.png" width="380" alt="Logo">
</p>

<p align="center">
  <em>Inspect • Test • Analyze</em><br>
  <strong>A Terminal-Based Web Inspection & Security Testing Lab - 2026 </strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.12.12-blue?logo=python" alt="Python">
  <img src="https://img.shields.io/badge/TUI Library-Textual-purple?logo=python&logoColor=white" alt="Textual">
  <img src="https://img.shields.io/badge/Library-Rich-orange?logo=python&logoColor=white" alt="Rich">
  <img src="https://img.shields.io/badge/Library-Aiohttp-green?logo=python&logoColor=white" alt="Aiohttp">
  
  <img src="https://img.shields.io/badge/Style-CSS-blue?&logoColor=white" alt="Aiohttp">
  <img src="https://img.shields.io/badge/Version-1.0-red" alt="Version">
  <img src="https://img.shields.io/badge/Platform-Termux%20|%20Linux%20|%20macOS-lightgrey" alt="Platform">
  <img src="https://img.shields.io/badge/Status-Active-success" alt="Status">
</p>

---

## 🧪 About Web Analyzer

**Web Analyzer** is a modern, terminal-based **web inspection & security testing lab** built using **Python** and **Textual**.  
It is crafted for **ethical hackers, cybersecurity learners, web testers, and developers** looking to explore HTTP internals.  

**Features a clean TUI for:**
- Crafting HTTP requests
- Analyzing server responses
- Generating and testing payloads
- Vulnerability assessment  

---

## ✨ Premium Highlights

- Fully interactive **Textual TUI** with keyboard shortcuts  
- HTTP Request Inspector with full method support  
- Advanced Payload Generator & Vulnerability Scanner  
- Encoder / Decoder utilities (Base64/32/16, URL, HTML Entities, JWT)  
- Session, cookie & request history management  
- Predefined request templates for JSON, GraphQL, API keys, file uploads  
- Clean dark-theme hacker-style interface  

---

## 🔧 Core Modules

### 🌐 HTTP Request Inspector
- Methods: `GET`, `POST`, `PUT`, `DELETE`, `PATCH`, `HEAD`, `OPTIONS`  
- Custom headers, cookies, parameters & body  
- Proxy support: HTTP / HTTPS / SOCKS4 / SOCKS5  
- SSL verification toggle & timeout control  

### 🔐 Encoder / Decoder Lab
- Base64 / Base32 / Base16 (Hex)  
- URL Encode / Decode  
- HTML Entities  
- JWT inspection  

### 🚀 Payload Generator
- SQL Injection, XSS, Command Injection, Directory Traversal, SSRF, XXE  
- Template Injection, NoSQL, LDAP, XPath Injection  
- Custom payload creation, preview, & save  

### 🛡️ Vulnerability Scanner
- Detect SQLi, XSS, Directory Traversal, Command Injection  
- CSRF token checks, missing security headers  
- Exportable JSON reports with severity & affected parameters  

### 🔍 Login Page Detector
- Auto-detect login forms  
- Discover username & password fields  
- Hidden input extraction  
- Ready-to-submit requests  

---

## ⌨️ Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| `Ctrl + Q` | Quit |
| `Esc` | Close modal |
| `Tab` | Switch focus |
| `Enter` | Confirm |
| `Ctrl + M` | Select HTTP method |
| `Ctrl + E` | Encoder / Decoder |
| `Ctrl + G` | Payload Generator |
| `Ctrl + V` | Vulnerability Scanner |
| `Ctrl + T` | Request Templates |
| `Ctrl + W` | Session Manager |
| `Ctrl + O` | Import response headers |
| `Ctrl + N` | Resend with edited headers |

---

## 📁 Project Structure

```

Web-Analyzer/
│
├── payloads_save/
│   └── payloads_<timestamp>.txt
├── vulnerability_scan_result/
│   └── vulnerability_scan_<timestamp>.json
├── request_history/
│   └── request_history_<timestamp>.json
├── Web_Analyzer_/
│   └── Web_Analyzer_style.css
├── MORE/
└── README.md

````

---

## ⚙️ Requirements

- Python **3.12.12**  
- Termux / Linux / macOS  

### Install Dependencies
```bash
pip install aiohttp textual beautifulsoup4
````

---

## ▶️ Run Web Analyzer

```bash
apt update && apt upgrade
pkg install python -y
pkg install python3 -y
pkg install git -y
git clone https://github.com/TEAMBCS/Web-Analyzer.git
cd Web-Analyzer
chmod +x *
chmod 777 *
chmod +w .
pip install -r web-analyzer.txt
python3 web-analyzer.py
```
*or*
```
bash start.sh
```

## 📸 Screenshots

<p align="center">
  <img src="https://raw.githubusercontent.com/TEAMBCS/Web-Analyzer/main/Logo%20and%20Screenshot/Web_Analyzer_pic1_v2.png" width="45%" alt="Screenshot 1">
  &nbsp;&nbsp;
   <img src="https://raw.githubusercontent.com/TEAMBCS/Web-Analyzer/main/Logo%20and%20Screenshot/Web_Analyzer_pic2.png" width="45%" alt="Screenshot 2">
  &nbsp;&nbsp;
  
  
</p>

---

## 📃 Note 

**Edit CSS Code as your wish.**

**If you found textual library install problem in kali linux machines or debian machines**
- use
```
pip install textual --break-system-packages --ignore-installed pygments
```
---

## ⚠️ Legal & Ethical Notice

**For authorized testing and educational purposes only**.

* Do not test without explicit permission
* Misuse may be illegal
* Author takes no responsibility for improper use

---

## 👤 Author Info

* Developer :**BLACK ZERO**
* GitHub: [BLACK-ZER-0](https://github.com/BLACK-ZER-0)
* Tool Owner : *BANGLADESH CYBER SQUAD* & *TEAM SHADOW STRIKER*

---

## ⭐ Support & Contribution

* ⭐ Star this repository
* 🔗 Share with learners
* 🛠 Contribute improvements or bug fixes



