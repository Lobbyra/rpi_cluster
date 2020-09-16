# rpi_cluster

![Imgur](https://imgur.com/a/PgiD3IG.jpg)

---

### Decription of this repository 📕

Here you will find dockerfile, manifest and sources of services that can be deployed on Raspberry Pi ARM 64 bits in Docker Swarm.

### The vision 👁

I'm creating a raspberry server that run a lot of services deployed in Docker Swarm.
For information i'm using the raspberry 4 with 8 go of ram. [Link to it](https://www.raspberrypi.org/products/raspberry-pi-4-model-b/)

I will create all Dockerfiles from Debian.
All this services have to be accessible by name_svc.hostrpi.com by proxy reversing and SSL protected.

### Ideas 💡

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
- DNS Server

Services be fun to deploy for tests :
- Pfsense
- Webmail hosting
- Minecraft Serveur
- Teamspeak server
- Active directory (LDAP) that work with windows, linux and macos.
- DHCP server
