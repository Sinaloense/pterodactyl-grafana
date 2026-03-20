# pterodactyl-grafana
Dockerfile y Egg para correr Grafana dentro de un servidor Pterodactyl.

## Contenido del repositorio:

- `Dockerfile` — Imagen con Nginx, PHP-FPM y scripts necesarios. (https://github.com/Sinaloense/pterodactyl-debian/blob/main/Dockerfile)
- `entrypoint.sh` — Script de arranque. (https://github.com/Sinaloense/pterodactyl-debian/blob/main/entrypoint.sh)
- `egg-grafana.json` — Egg para usar en Pterodactyl.

## Características

- Grafana version: `12.4.1`.

## Requisitos:

- Pterodactyl installed.

## Instalación:

- Carga `egg-grafana.json` en tu panel.

## Recomendado usarse en conjunto con:

- [Pterodactyl Cloudflared.](https://github.com/Sinaloense/pterodactyl-cloudflared)
