# 🛡️ Agila Auth Keep-Alive

[![Keep Auth Service Alive](https://github.com/JM-Garces/agila-auth-keep-alive/actions/workflows/keep-alive.yml/badge.svg?event=workflow_dispatch)](https://github.com/JM-Garces/agila-auth-keep-alive/actions/workflows/keep-alive.yml)

A simple GitHub Actions workflow that automatically sends a login request every 6 minutes to keep the Agila authentication service awake (useful for free-tier hosting that sleeps on inactivity).

---

## 🔧 How It Works

- Triggers every 6 minutes using GitHub Actions.
- Sends a POST request to `/api/auth/login` endpoint.
- Prevents the server from going idle.

---

## 📂 Repository Structure
.github/
workflows/
keep-alive.yml # GitHub Actions workflow

---

## 🚀 Manual Trigger

You can also trigger it manually from the [Actions tab](https://github.com/JM-Garces/agila-auth-keep-alive/actions/workflows/keep-alive.yml).

