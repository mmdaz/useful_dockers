# Graylog docker-compose
## Run follow commands
```
sudo mkdir -p ./volumes/dynamic/
sudo mkdir -p ./volumes/static/
sudo cp prometheus.yml ./volumes/static/
sudo cp entrypoint.sh ./volumes/static/
```
###### Add your target to prometheus config
```
vim ./volumes/static/prometheus.yml
```
###### Run docker
```
docker-compose up -d
```
