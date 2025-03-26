# node-ts-hello

```
podman build -t=node-ts-dev:latest .
podman run -v "$(pwd):/code" localhost/mytsdev node dist/index.js
```