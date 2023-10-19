---
description: >-
  If you need to execute a manual Docker compose installation process you can
  follow the instructions.
---

# Manual Docker compose installation

You need to have Docker Engine and Docker Compose on your machine. You can either:

* Install [Docker Engine](https://docs.docker.com/get-docker/) and [Docker Compose](https://docs.docker.com/compose/install/) as standalone binaries or
* Install [Docker Desktop](https://docs.docker.com/desktop/) which includes both Docker Engine and Docker Compose
* Installation instructions specific for [Docker Engine](https://docs.docker.com/engine/install/debian/) on Debian

You don't need to install Python or Redis, as Docker images provide both.

1. Download the archive from your [EasyPON personal cabinet account](https://cabinet.easypon.in/) license, unpack the archive, and go to the unpacked directory by using the commands.

```bash
tar -xvf easypon.tar 
cd easypon
```

2. Create env files

```bash
touch .env_docker
touch .env
```

2. Build images with the following command:

```bash
docker compose build
```

3. Generate .env\_docker

```bash
docker run --rm easypon-backend init > .env_docker 
```

4. Start your project

```bash
docker compose up -d 
```

5. To create an admin user, utilize the login and password from the environment variables specified in the `.env_docker` file:

```bash
docker compose exec -ti backend_main bash compose/backend-entry-point.sh create_user
```
