# pnpm docker image

Packages installed:
* NodeJS 18 alpine
* [pnpm 8.x](https://www.npmjs.com/package/pnpm)

### Build docker image
```shell
docker build -t pnpm:alpine .
```

### Push the image
Once merged with main, a workflow will be triggered for build and publish the docker image in different Registries: 
* [Docker HUB](https://hub.docker.com/r/fernandoarteaga/pnpm)
* [GitHub Container Registry](https://github.com/orgs/Goats-Tech/packages?repo_name=docker-images)
