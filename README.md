# My Quasar Express App (Lab 1.1)

โปรเจกต์สำหรับ **Lab 1.1 — สร้างและรัน Quasar Frontend ด้วย Git, Docker และ Docker Compose**

## โครงสร้างโปรเจกต์

- `frontend/` — Quasar Frontend Application (Vue 3 + Quasar CLI Vite)
- `docker-compose.yml` — การตั้งค่า Docker Compose สำหรับรันบริการ `frontend`

## การรันในโหมดพัฒนา

```bash
cd frontend
npm install
npm run dev
```

## การรันด้วย Docker Compose

```bash
docker compose up -d --build
```
