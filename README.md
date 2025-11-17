#  My-Internet-Tester

*A clean, modern, and reliable browser-based tool to check your internet's online status, latency, and network details.*

👉 **Live Demo:**  

---

## 🚀 Features

### ✅ Real-Time Internet Status  
Instantly tells you whether your internet is:

- **YES!** – Online  
- **NO!** – Offline  
- **WAIT!** – Checking...

### 🌐 Network Statistics  
Displays:

- **IPv4 Address**  
- **ISP Name**  
- **Location** (City, Region, Country)  -- [work in progress]
- **ASN (Autonomous System Number)**  

### ⚡ Latency (Ping) Test  
Measures latency using global CDN endpoints such as:

- Google `generate_204`  
- Google `clients3`  
- Cloudflare Trace  

Runs multiple attempts and uses the **median** latency for accuracy.

### 🧭 DNS Resolution Test  
Performs DNS lookup speed tests using DNS-over-HTTPS (DoH):

- Cloudflare DoH  
- Google DoH  

Shows the **median DNS resolution time**.

### 📉 Jitter Test  
Run a complete stability test for:

- **30 seconds**  
- **1 minute**  
- **2 minutes**

Includes:

- Jitter  
- Average Latency  
- Minimum Latency  
- Maximum Latency  

### 🔁 Auto-Refresh  
Automatically re-runs the ping test at:

- **2 seconds**  
- **5 seconds**  
- **10 seconds**  
- **15 seconds**

### 📱 Fully Responsive  
Works smoothly on:

- Desktop  
- Tablet  
- Mobile  

---

## 🛠 Tech Stack

This project uses:

- **HTML5**  
- **Tailwind CSS**  
- **JavaScript (ES6+)**  
  - Fetch API  
  - DNS-over-HTTPS  
  - navigator.onLine  
  - performance.now()
 
## 👨‍💻 Author

Developed by **Biraj Sarkar**.  
Give the repo a ⭐ if you like the project!
