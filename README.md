# 🚀 Ubuntu Server ZeroTrust Stack

## 📌 Overview

This project demonstrates a secure, self-hosted DevOps architecture built on **Ubuntu Server**. It uses **Coolify** as a self-hosted PaaS to deploy a **Node.js backend** and **MySQL database** inside an isolated Docker environment.

The system is protected using **Cloudflare Zero Trust tunnels**, ensuring no public ports are exposed and the server IP remains hidden.

---

## 👨‍💻 Author

* **Name:** Hazem Hamdi Mahmoud Abdelqader
* **University:** Nahda University (NUB)
* **Faculty:** Engineering
* **Department:** Communications and Electronics

### 📬 Contact

* 📧 Email: [hazemhamdypersonal@gmail.com](mailto:hazemhamdypersonal@gmail.com)
* 📱 Phone: +20 106 238 6571
* 💻 GitHub: https://github.com/Hazem-Hamd

---

## 🧱 Architecture

* Ubuntu Server (Base OS)
* SSH (Secure access)
* Coolify (Self-hosted PaaS)
* Docker (Containers)
* Node.js (Backend)
* MySQL (Database)
* Cloudflare Tunnel (Zero Trust Security)
* Custom Domain (Namecheap)

---

## ⚙️ Tech Stack

* Ubuntu Server → https://ubuntu.com/download/server
* Coolify → https://coolify.io
* Cloudflare Tunnel → https://developers.cloudflare.com/cloudflare-one/
* Docker → https://www.docker.com/
* Node.js → https://nodejs.org/
* MySQL → https://www.mysql.com/

---

## 🏗️ Setup

### 1. Server Setup

* Install Ubuntu Server
* Configure static IP
* Install minimal packages

### 2. Remote Access

```bash
ssh user@server_ip
```

### 3. Install Coolify

```bash
curl -fsSL https://cdn.coollabs.io/coolify/install.sh | sudo bash
```

### 4. Deploy App

* Create MySQL database
* Deploy Node.js backend
* Use Docker internal networking

### 5. Domain Setup

* Buy domain from Namecheap
* Example:

```
yourdomain.online
```

### 6. Cloudflare Tunnel

```bash
wget https://github.com/cloudflare/cloudflared/releases/latest/download/cloudflared-linux-amd64.deb
sudo dpkg -i cloudflared-linux-amd64.deb
```

```bash
cloudflared --version
```

---

## 🔐 Security

* No open ports
* Encrypted connections (SSH + HTTPS)
* Hidden server IP
* DDoS protection via Cloudflare
* Zero Trust architecture

---

## 🌍 Benefits

* Secure and private infrastructure
* Easy deployment with Coolify
* Scalable Docker-based system
* Clean domain access
* Fully self-hosted

---

## 📊 Use Cases

* Backend API hosting
* Secure databases
* Personal cloud
* DevOps practice

---

## 📌 Summary

A modern, secure, and scalable backend infrastructure combining:

* Self-hosting
* Cloud-level security
* DevOps best practices
