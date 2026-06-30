# HTTP vs HTTPS – Security Demo
**Mini Project | Dr. D.Y. Patil Institute of Technology, Pimpri, Pune**  
Students: Nikita Shinde · Vaishnavi Nikam · Sanika Patil · Siddesh Choulwar  
Faculty: Prof. Ifrah Sutar

---

## 📁 Project Structure

```
http-vs-https/
├── index.html              ← Homepage
├── css/
│   └── style.css           ← All styles
├── js/
│   └── main.js             ← Shared JavaScript
└── pages/
    ├── compare.html        ← Protocol Comparison Table
    ├── dataflow.html       ← Animated Data Flow Visualizer
    ├── login-sim.html      ← Interactive Login Simulator ⭐
    ├── attacks.html        ← Attack Demos (MITM, Sniffing...)
    └── tls.html            ← SSL/TLS Concepts
```

---

## 🚀 How to Run in VS Code

### Option 1: Live Server (Recommended)
1. Open VS Code
2. Install the **Live Server** extension (by Ritwick Dey)  
   → Press `Ctrl+Shift+X` → search "Live Server" → Install
3. Open the project folder in VS Code:  
   `File → Open Folder → select http-vs-https/`
4. Right-click `index.html` → **"Open with Live Server"**
5. Browser opens at `http://127.0.0.1:5500`

### Option 2: Just Open the File
- Simply double-click `index.html` — it opens in your browser directly.
- All pages work without any server.

---

## 🌐 Deploy to Netlify (for HTTPS)

1. Go to [netlify.com](https://netlify.com) and sign up (free)
2. Click **"Add new site" → "Deploy manually"**
3. Drag and drop the entire `http-vs-https/` folder
4. Netlify auto-assigns an HTTPS URL with free SSL ✅

---

## 📋 Pages Overview

| Page | Description |
|------|-------------|
| `index.html` | Homepage with hero section and navigation |
| `compare.html` | Side-by-side feature comparison table |
| `dataflow.html` | Animated packet flow (HTTP vs HTTPS) |
| `login-sim.html` | Type credentials and see HTTP exposure vs HTTPS encryption |
| `attacks.html` | MITM, Sniffing, Session Hijacking, SSL Stripping |
| `tls.html` | TLS Handshake, Certificates, Encryption types |

---

## 🛠 Technologies Used
- HTML5, CSS3, Vanilla JavaScript
- Google Fonts (Share Tech Mono, Rajdhani)
- No frameworks, no dependencies — runs anywhere!
