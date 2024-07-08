# Docker Zoneminder

Docker implementation using official zoneminder-base image with some addtional config definitions.

Based on:

- https://github.com/zoneminder-containers/zoneminder-base
- https://github.com/jantman/docker-zoneminder

## How-to

- Clone the repo
- Edit & improve docker-compose.override.yml file with yours definitions.
- Run:

```sh
docker-compose pull && docker-compose down && docker-compose up -d --remove-orphans
# OR
docker compose pull && docker compose down && docker compose up -d --remove-orphans
```
