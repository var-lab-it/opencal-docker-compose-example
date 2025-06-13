# Run OpenCal in docker-compose

This is an example how to get running OpenCal (frontend & backend) with docker-compose.

It is simple to use:

1. Pull this repo

```bash
git clone git@github.com:var-lab-it/opencal-docker-compose-example.git
```

2. Create .env-file

```bash
cp .env.dist .env
```

(and adjust it if required).

3. Run it

```bash
docker compose up -d
```

## Update

Just run

```bash
docker compose pull
```

and then

```bash
docker compose up -d
```
