🚀 Infrastructure & Deployment Architecture
📌 Overview

This project demonstrates the design and implementation of a secure, self-hosted web infrastructure using modern DevOps tools and best practices.

The system is built on Ubuntu Server, managed through a self-hosted PaaS, and secured using a Zero Trust architecture. It is designed to host a Node.js backend with a MySQL database without exposing sensitive ports to the public internet.

👨‍💻 Author Information
Name: Hazem Hamdi Mahmoud Abdelqader
University: Nahda University (NUB)
Faculty: Engineering
Department: Communications and Electronics
📬 Contact
📧 Email: hazemhamdypersonal@gmail.com
📱 Phone: +20 106 238 6571
💻 GitHub: https://github.com/Hazem-Hamd
🧱 Architecture Overview

The infrastructure consists of:

Ubuntu Server (Base OS)
SSH (Secure remote access)
Coolify (Self-hosted PaaS)
Docker Containers (App + Database)
MySQL (Database)
Node.js (Backend API)
Cloudflare Tunnel (Zero Trust Security)
Custom Domain (Namecheap)
⚙️ Tools & Technologies
Tool	Description	Link
Ubuntu Server	Linux-based server OS	https://ubuntu.com/download/server

Coolify	Self-hosted PaaS platform	https://coolify.io

Cloudflare Tunnel	Secure Zero Trust access	https://developers.cloudflare.com/cloudflare-one/connections/connect-apps/

Namecheap	Domain registration	https://www.namecheap.com/

Docker	Containerization platform	https://www.docker.com/

Node.js	Backend runtime	https://nodejs.org/

MySQL	Relational database	https://www.mysql.com/
🏗️ Deployment Steps
1️⃣ Server Setup
Install Ubuntu Server
Configure static IP
Install minimal packages
2️⃣ Secure Remote Access
ssh user@server_ip
Uses encrypted SSH connection
Allows secure remote management
3️⃣ Install Coolify (PaaS)
curl -fsSL https://cdn.coollabs.io/coolify/install.sh | sudo bash
Deploy apps easily
Manage Docker containers visually
4️⃣ Database & Backend Deployment
Create MySQL database inside Coolify
Deploy Node.js app
Internal Docker networking ensures security
5️⃣ Domain Setup
Purchase domain from Namecheap
Example:
yourdomain.online
6️⃣ Cloudflare Tunnel Setup

Install cloudflared:

wget https://github.com/cloudflare/cloudflared/releases/latest/download/cloudflared-linux-amd64.deb
sudo dpkg -i cloudflared-linux-amd64.deb

Verify:

cloudflared --version
Connect server to Cloudflare
Route traffic securely without opening ports
🔐 Security Features
❌ No open ports (no port forwarding)
🔒 Encrypted connections (SSH + HTTPS)
🌐 Hidden server IP
☁️ Cloudflare DDoS protection
🔑 Zero Trust architecture
🌍 Key Benefits
High security with minimal exposure
Easy deployment using Coolify
Scalable container-based architecture
Clean domain-based access (no raw IPs)
Fully self-hosted solution
📊 Use Cases
Hosting backend APIs
Secure database systems
Personal cloud infrastructure
DevOps learning projects
📌 Conclusion

This project demonstrates how to build a modern, secure, and scalable infrastructure using open-source tools and cloud-based security layers.

It combines:

Self-hosting power
Cloud-level security
Developer-friendly deployment
