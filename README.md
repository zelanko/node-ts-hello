# node-ts-hello

```
podman container run --mount=bind,src=../node-ts-hello,dst=/code --name=node-ts-dev docker.io/library/node@22-alpine3.21 node /code/dist/index.js
podman start node-ts-dev;
```

```
podman container create --name=mydev --replace node node --version
podman container start mydev
```