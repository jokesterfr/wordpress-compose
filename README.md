# Cairns Wordpress

Le CAIRNS est une association Savernoise d'escalade. Ceci est le petit script pour lancer le site web via docker. Rien de très compliqué !

À bientôt sur les voies de grès rose.

## Setup

### Requirements

- Docker
- Docker-compose

### Setup

```bash
cp .env.dist .env
docker-compose up -d
```

## Usage

### Access

```bash
docker-compose exec cairns-wordpress bash
```

### Update

```bash
docker-compose pull
docker-compose up -d
```

## License

MIT
