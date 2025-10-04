# node-ts-hello
Node-typescript hello world you can run as docker container.

## build
```
podman build -t=node-ts-dev:latest .
podman run -v "$(pwd):/code" localhost/mytsdev node dist/index.js
```
