# Kafka, SSL, docker compose

Docker-compose file and scripts for two Way Kafka SSL.

## Usage

0. Make sure keytool installed.

In debian 12 system

```
sudo apt install openjdk-17-jre
```   
2. Execute `./create-certs.sh` to generate self-signed CA and certs.
3. Run `docker-compose up` to start.


