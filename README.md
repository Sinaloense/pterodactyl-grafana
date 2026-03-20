# pterodactyl-grafana
Dockerfile and Egg to run Grafana inside a Pterodactyl server.

## Repository contents

- `Dockerfile` — Image with cloudflared and required scripts. (https://github.com/Sinaloense/pterodactyl-debian/blob/main/Dockerfile)
- `entrypoint.sh` — Startup script. (https://github.com/Sinaloense/pterodactyl-debian/blob/main/entrypoint.sh)
- `egg-grafana.json` — Egg to use in Pterodactyl.

## Features

- Grafana version: `12.4.1`.

## Requirements

- Pterodactyl installed.

## Installation

- Upload `egg-grafana.json` to your Pterodactyl panel.

## Recommended to be used together with

- [Pterodactyl Cloudflared.](https://github.com/Sinaloense/pterodactyl-cloudflared)
