# rpi_cluster

I'm creating a raspberry server that run a lot of services deployed in Docker Swarm.
For information i'm using the raspberry 4 with 8 go of ram. [Link to it](https://www.raspberrypi.org/products/raspberry-pi-4-model-b/)

I will create all Dockerfile from Debian.

All this services have to be accessible by name_svc.hostrpi.com by proxy reversing.

Services planned :
- Nginx with php available and HTTPS
- FTPS
- many wordpress / mariadb / phpmyadmin with HTTPS
- Python code executors
- influxdb
- Telegraf that measure system metrics of the raspberry.
- Grafana that will display metrics in influxDB with HTTPS
- Nodejs code executors
- VPN server
- Git server

Services be fun to deploy for tests :
- Pfsense
- Webmail hosting
- Minecraft Serveur
- Teamspeak server
