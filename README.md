# Docker Stuff

"Docker-Stuff" is a project that provides a collection of example files for NGINX configurations and Docker configurations.
Here you can find docker images, docker compose files and nginx configurations. Mostly docker related stuff.

I use these things myself for "private" purposes and may become obsolete when I no longer use them.

You can open a ticket if you have any questions or if something is out of date or an tutorial is needed, how to use and purposes.

---

## Helpful things

### Docker Commands

Essential Docker commands for managing containers: starting, logging, stopping, and executing commands.

```sh
docker compose up -d
docker compose logs -f
docker compose down
docker compose down --volumes --rmi all
```

> [!CAUTION]
> --volumes remove all volumes
> --rmi all remove all images too.

```sh
docker exec -it <container> /bin/bash
docker exec -it <container> /bin/sh

docker compose exec <service> <command>
```

---

## Structure

### Docker compose files

Here are docker-compose.yml files to support different applications. The Nginx configurations could be helpful here

Additional docker compose files can be found at [PAPAMICA](https://github.com/PAPAMICA/docker-compose-collection)

### Config

Is not exclusively for docker purposes but exists probably because of the docker compose files purposes.

## Pterodactyl Images

Docker images that can be used with the Pterodactyl egg system. You can request more images by opening a new issue.

Additional Pterodactyl images can be found at [Software-Noob](https://github.com/Software-Noob/pterodactyl-images), [Parkervcp](https://github.com/parkervcp/images), [Matthewpi](https://github.com/matthewpi/images) and [Yolks](https://github.com/pterodactyl/yolks) repositories.

> [!NOTE]  
> Some links may be outdated.

These Pterodactyl images probably exist because of this repository [keksgauner/eggs](https://github.com/keksgauner/eggs)

### CloudNet [AMD64]

- [CloudNet](https://github.com/keksgauner/docker-stuff/tree/main/pterodactyl/images/cloudnet)
  - `keksgauner/cloudnet:latest`
  - `hub.docker.com/r/keksgauner/cloudnet`
