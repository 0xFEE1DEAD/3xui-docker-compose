# Docker 3xui + traefik ssl webinterface for VPN

1. Create and configure .env file
```bash
cp .env.example .env
nano .env
```

2. Start app
```bash
docker compose up -d
```

3. If it has been configured correctly, you should go to `https://${ROOT_DOMAIN}:${WEB_PORT}` to set up 3xUI.

4. Complete 3xui settings
* change admin password
* change xui url