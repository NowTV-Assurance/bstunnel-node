## Dockerfile Image for Browserstack Tunnel and Node

Useful for things like Selenium tests with NightwatchJS

## To use

```
FROM nowtvassurance/bstunnel-node:6.9.5
```

## To build

```bash
node_version=6.9.5

docker build \
  --build-arg NODE_VERSION=${node_version} \
  -t nowtvassurance/bstunnel-node:${node_version} \
  .
```

## Questions

If you want another version of node building, just make an issue on Github and we'll be happy to build it.