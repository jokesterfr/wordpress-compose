# Wordpress compose

This is a simple project to deploy Wordpress with Docker.

* This Wordpress configuration is meant to run on HTTPS only, please consider using Let's encrypt to get a free SSL certificate.
* This setup rely on docker volumes to persist data, don't forget to backup your volumes on a regular basis.

## Requirements

- Docker

> Disclaimer: always use `docker compose` rather than `docker-compose`

## Setup

```sh
cp .env.dist .env
docker-compose up -d
```

## Usage

Go to `https://<your-domain>/wp-admin/`

## License

MIT
