# postgres-exporter docker-compose
###### Run follow commands
```
sudo mkdir -p ./volumes/static/
sudo cp grafana.ini ./volumes/static/
docker-compose up -d
```

###### Environment Variables
```
GF_SERVER_ROOT_URL=YOUR_SERVER_IP
GF_SECURITY_ADMIN_PASSWORD=PASSWORD

```
