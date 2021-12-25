# Traefik for single server

This module includes:
- Traefik 2.5.6
- Dashboard enabled with SSL and protected by middleware authelia
- Automatically restart when it got crashed or startup
- Run on *traefik* network

```bash
# Create a new network for traefik
docker network create traefik		# Create a traefik network
docker-compose up -d			# Spin up containers
```
