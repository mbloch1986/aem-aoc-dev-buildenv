A collection of Dockerfiles to support developing for AEM OpenCloud.

Centos 8 is used as base image.

Command to build an image for INTEL/AMD64.
```
docker build -t aoc-dev-amd64:latest -f Dockerfile-amd64 .
```

Command to build an image for ARM64.
```
docker build -t aoc-dev-arm64:latest -f Dockerfile-arm64 .
```
