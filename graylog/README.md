# Graylog docker-compose
## Run follow commands
```
sudo mkdir -p ./volumes/dynamic/graylog/graylog_journal
sudo chown 1100:1100 -R ./volumes/dynamic/graylog/graylog_journal
sudo mkdir -p ./volumes/static/config
sudo chown 1100:1100 -R ./volumes/static/config
```
###### Costomize docker-compose.yml
```
docker-compose up -d
```
