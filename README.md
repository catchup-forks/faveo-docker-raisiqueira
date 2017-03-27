# Faveo HelpDesk Docker Image

simple Docker image to run a Faveo HelpDesk app.

## Build
Build from `docker-compose.yml`, or pull from Docker Hub: `docker pull raisiqueira/faveo-imec`.

## Running
- Rename `example.env` to `.env`.
- run `docker exec app-faveo php artisan key:generate`.

| :whale: Docker Hub     | Link                                             |
|------------------------|--------------------------------------------------|
| raisiqueira/faveo-imec | https://hub.docker.com/r/raisiqueira/faveo-imec/ |

Thank's to [Ambientum](https://github.com/codecasts/ambientum) PHP 7.0.x image.