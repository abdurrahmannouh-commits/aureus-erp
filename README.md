# Aureus ERP (Docker Setup)

Habka Docker-ka loogu kiciyo Aureus ERP gudaha Zorin OS / Linux.

## 🚀 Sida loo kiciyo (Quick Start)

1. **Kici xarunta (Start Containers):**
   ```bash
   docker compose up -d
   ```

2. **Fur Browser-kaaga:**
   * URL: [http://localhost:8085](http://localhost:8085)

3. **Faahfaahinta Galitaanka (Default Login Credentials):**
   * **Email:** `admin@example.com`
   * **Password:** `admin@123` *(ama `admin123`)*

---

## 🐳 Whaler Management
Waxaad si toos ah uga arki kartaa una maamuli kartaa container-ka **aureus-erp** abka **Whaler**:
* Start / Stop / Restart
* View Logs
* Terminal Access

---

## ⚙️ Dekadaha (Ports)
* **Web UI:** `8085` (maadaama dekadaha 80, 8080, iyo 8069 ay ku mashquulsan yihiin Caddy, ERPNext, & Odoo).
* **MySQL Database:** `3307` (dekadda 3306 waxaa isticmaalaya MariaDB).

---

## 🛑 Joojinta (Stop)
```bash
docker compose down
```
*(Xogtaadu ma lumayso maxaa yeelay waxay ku keydsan tahay Docker volumes).*
