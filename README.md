# Local Development Environment (Postgres, MongoDB, Redis)

Ushbu konfiguratsiya **Postgres**, **MongoDB** va **Redis** xizmatlarini `docker-compose` orqali local/test muhitda ishga tushirish uchun mo‘ljallangan.

---

## 📦 Talablar
- Docker (20+ versiya tavsiya etiladi)
- Docker Compose (2+ versiya)

---

## 🚀 Xizmatlarni ishga tushirish

1. Repository’ni clone qiling yoki `docker-compose.yml` faylini loyihangizga qo‘shing.

2. Terminalda quyidagi buyruqni bajaring:

```bash
docker compose up -d
```
3. Containerlar fon rejimida ishga tushadi. Holatini tekshirish uchun:

```bash
docker ps
```

4. To‘xtatish uchun:

```bash
docker compose down
```

### Connection info:

```dotenv
# PostgreSQL
POSTGRES_USER: test_user
POSTGRES_PASSWORD: test_password
POSTGRES_DB: test_db

# MongoDB
MONGO_INITDB_ROOT_USERNAME: test_user
MONGO_INITDB_ROOT_PASSWORD: test_password
```
