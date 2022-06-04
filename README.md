# nginx-proxy-manager-docker-compose

```bash
cat <<EOT >> .env
HTTP_PORT=80
ADMIN_PORT=81
HTTPS_PORT=443
MYSQL_ROOT_PASSWORD=password
MYSQL_USER=user
MYSQL_PASSWORD=password
EOT

sudo docker-compose up -d
```
