# node-ts-hello

```
podman container run --name=node-ts-dev docker.io/library/node@22-alpine3.21 node --version
podman start node-ts-dev;
```

```
podman container create --name=mydev --replace node node --version
podman container start mydev
```

```
podman build -t=node-ts-dev:latest .
podman run -v "$(pwd):/code" localhost/mytsdev node dist/index.js
```