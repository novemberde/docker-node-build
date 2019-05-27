# docker-node-build
Docker images for building nodejs application. Installed every packages required based on alpine linux. (node-gyp, git, awscli, nodejs, npm, docker in docker, golang, python3, pip3)

## Usage

```sh
$ docker run -it --privileged --rm --name node-build novemberde/node-build:10.15.3-alpine echo "Hello world"
```

## Installed packages

### Essentials

- git
- bash
- build-base
- libffi-dev
- openssl-dev
- bzip2-dev
- zlib-dev
- readline-dev
- sqlite-dev
- openssh

### Languages

- Python3 & pip3
- Node.js & NPM: 10.15.3
- Golang: 1.12.5

### Support environments

- Docker


## [LICENSE](/LICENSE)