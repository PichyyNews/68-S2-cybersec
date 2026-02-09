# Cyber Security

## Information
- Pichayut Somboon (พิชญุตย์ สมบุญ)
- 6702041510113
- email : s6702041510113@email.kmutnb.ac.th

## Environment
```bash
cp .env.example .env
# Edit .env to match your credentials
```

## Running service

1. **Enter Project Directory** & **Checkout Branch**:
   ```bash
   cd 68-S2-cybersec
   git checkout develop
   ```

2. **Run Services**:

   ### Database
   ```bash
   docker compose -f db.yaml up -d
   ```

   ### Admin
   ```bash
   docker compose -f admin.yaml up -d
   ```

   ### Application
   ```bash
   docker compose -f app.yaml up -d
   ```
