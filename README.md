# Docker-Compose-Nginx-Proxy-Template
A Docker Compose Template for automated configuration of multiple HTTPS websites on a single Virtual Private Server with Nginx.

## This container...
- Sets up a nginx reverse-proxy and generates a Nginx config for each website to link a domain name and a container.
- Creates and renews SSL certificates to enable HTTPS on each website.

### Run
```shell 
docker compose up -d
```
