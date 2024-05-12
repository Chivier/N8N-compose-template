# N8N-compose-template

Quickly deploy n8n on a server

## Before use

1. Remember update files in your n8n .env file for environment variables.
2. Remember update EMAIL in traefik docker-compose file
3. Create external network and external volume

```bash
docker network create traefik
docker volume create --name=traefik_data
```


