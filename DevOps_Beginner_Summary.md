# DevOps Beginner Summary

## Ubuntu Server
- A Linux operating system commonly used on cloud servers.
- Think of it as the **building** where your application lives.

## Node.js
- A JavaScript runtime that executes your backend code.
- Think of it as the **chef** who cooks using your recipes (code).

## Express App
- Your actual backend application.
- Handles requests and returns responses.

## PM2
- A **process manager** that keeps your app running.
- Automatically restarts the app if it crashes or the server reboots.
- Think of it as the **restaurant manager**.

## Nginx
- A **web server** and **reverse proxy**.
- Receives requests from users and forwards them to your app.
- Handles HTTPS, serves static files, and can load balance traffic.
- Think of it as the **receptionist**.

## Deployment Flow

```text
User
  ↓
DNS
  ↓
Domain
  ↓
Ubuntu Server
  ↓
Nginx
  ↓
PM2
  ↓
Node.js
  ↓
Express App
  ↓
Database
```

## One-Line Recap

| Component | Purpose |
|-----------|---------|
| Ubuntu Server | Operating system for the server |
| Node.js | Runs JavaScript backend |
| Express | Your backend application |
| PM2 | Keeps the app running |
| Nginx | Routes traffic and handles HTTPS |
| Database | Stores application data |

### Easy Analogy
- **Ubuntu** = Building
- **Node.js** = Chef
- **Express** = Restaurant
- **PM2** = Manager
- **Nginx** = Receptionist
- **Users** = Customers
