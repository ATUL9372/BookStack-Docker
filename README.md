# 📘 BookStack - Self-Hosted Wiki Platform

BookStack is a free, open-source platform for creating and organizing documentation and wiki content. Ideal for internal team docs, IT manuals, SOPs, or personal knowledge bases.

## 🛠 Features
- 🗂 Hierarchical content (Books > Chapters > Pages)
- ✍️ Easy WYSIWYG & Markdown editing
- 🔐 User roles & permissions
- 🔎 Powerful search & navigation
- 🌐 API integration
- 🌙 Dark mode
- 💾 Self-hosted control

## 🚀 Quick Start with Docker
```bash
docker run -it --rm --entrypoint /bin/bash lscr.io/linuxserver/bookstack:latest appkey

git clone https://github.com/ATUL9372/BookStack-Docker.git
cd BookStack-Docker
docker-compose up -d

## 🔑 Default Login Credentials

Email : admin@admin.com
Password : password
