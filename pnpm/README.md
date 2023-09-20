# pnpm docker image

Packages installed:
* NodeJS 18 alpine
* [pnpm 8.x](https://www.npmjs.com/package/pnpm)

### Build the image
```shell
docker build -t fernandoarteaga/pnpm:alpine .
```

### Push the image
Once merged with main, a workflow will be triggered for build and publish the docker image into Docker Hub, as 
[fernandoarteaga/pnpm](https://hub.docker.com/r/fernandoarteaga/pnpm)
