# Cybersecurity Roadmap 🚀

An interactive, cyberpunk-themed learning roadmap designed for aspiring cybersecurity professionals. This single-page HTML application guides you through a structured, multi-phase curriculum—from Linux fundamentals and network protocols to web application security, defensive operations, and Active Directory hacking.

## 📸 Overview

The Roadmap features a custom **Sec-Ops Terminal V3.2 HUD** interface with:
- **Scanlines & CRT Effects:** Authentic retro-terminal aesthetic.
- **Neon Glow & Cyberpunk Colors:** Unique color coding for every learning phase.
- **Progress Tracking:** Persistent state (via `localStorage`) tracks your completion percentage, ranks, and badges.
- **Interactive Labs & Study Nodes:** Clear, actionable items for each phase broken down into "Learn First" (theory) and "Then Build" (tactical labs).
- **Dynamic Scrollspy HUD:** The top navigation bar dynamically highlights the active module as you scroll.
- **Left Index Rail:** Quick jump points for easy navigation through the curriculum.

## 🎯 The Curriculum (Phases)

1. **Foundations: Linux, Sockets, Lab Setup**
   *Learn the Linux shell, socket programming, threading, and VM setup via OverTheWire and custom scripts.*
2. **Network Interactions & Protocols**
   *Understand ARP, DNS, HTTP, and Nmap basics. Build your own multi-threaded port scanner.*
3. **Network Attacks & Basic Exploiting**
   *Deep dive into Metasploit, Nmap Scripting Engine, password cracking, and ARP spoofing.*
4. **Web Application Security**
   *Master Burp Suite, SQL injection, XSS, and command injection via OWASP Top 10 concepts.*
5. **Defensive Security**
   *Learn detection concepts, Wireshark filters, SIEM basics, and incident response.*
6. **Windows & Active Directory**
   *Understand AD domains, PowerShell, Kerberos authentication, and BloodHound.*
7. **Cloud Architecture & Hacking Basics**
   *Navigate IAM, AWS/Azure misconfigurations, and cloud-specific attack vectors.*

## 🚀 How to Run

This project is a completely standalone, zero-dependency, single-file web application. 

1. **Download or clone** this repository.
2. **Open `index.html`** in any modern web browser (Chrome, Firefox, Edge, Safari).
3. Start checking off your study and project items. Your progress is saved automatically to your browser's local storage.

## 🛠️ Features & Controls

* **Global Search:** Quickly filter nodes by typing in the search bar (e.g. "Wireshark", "Docker", "SQLi").
* **Filter Views:** Toggle between viewing `All`, `Pending`, `Completed`, `Labs Only`, or `Study Only`.
* **Prerequisite Locking:** Advanced modules remain locked until you complete their prerequisites.
* **Responsive Design:** Operates beautifully on desktop, tablet, and mobile displays.
* **Visual Effects Toggle:** Use the `[THEATRE MODE]` button to disable CRT scanlines for a cleaner, modern look.
* **Auto-Scrolling Sticky Bar:** The horizontal phase strip auto-scrolls and centers to keep your current focus in view.

## 💻 Tech Stack

- **HTML5**
- **CSS3** (CSS Variables, Flexbox/Grid, Animations, Scroll-behavior)
- **Vanilla JavaScript** (No external frameworks, direct DOM manipulation)

## 📄 License

This project is open-source and intended for educational purposes. Feel free to fork, modify, and build upon it to create your own specialized roadmaps!
