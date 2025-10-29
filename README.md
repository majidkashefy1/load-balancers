# 🧠 NGINX Load Balancer Algorithms Demo (Dockerized)

This project is a **hands-on demo** of different **load balancing algorithms** using **NGINX** and **Docker Compose**.  
It allows you to test and compare multiple strategies — all running locally on different ports.

---

## 🚀 Features

✅ Fully Dockerized (no manual installs needed)  
✅ 6 Load Balancing Algorithms  
✅ Visual testing via multiple ports  
✅ Lightweight, runs anywhere  
✅ Ideal for learning, teaching, or experimentation  

---

## ⚙️ Algorithms Included

| Port | Algorithm | Description |
|------|------------|-------------|
| `8080` | **Round Robin** | Requests distributed sequentially (S1 → S2 → S3 → …) |
| `8081` | **Weighted Round Robin** | Servers receive traffic based on defined weights |
| `8082` | **Least Connections** | Sends new requests to the least busy server |
| `8083` | **IP Hash** | Ensures the same client IP always reaches the same backend |
| `8084` | **Random** | Random server chosen for each request |
| `8085` | **Consistent Hash** | Same client or resource maps consistently, even if servers change |

---

## 🧱 Architecture

