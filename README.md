# centos-rvm-nvm

[![Docker Build Status](https://img.shields.io/docker/build/salihan/centos-rvm-nvm.svg)]()

A Docker image for CentOS with RVM and NVM installed

CentOS, Ruby and Node versions can be passed as build arguments

Build:
```
docker build --build-arg centos_ver=7 --build-arg ruby_ver=2.3.6 --build-arg node_ver=8.9.3 --rm -f Dockerfile -t centos-rvm-nvm:latest .
```

Current Image Size: 1.03GB

## ToDo
- [ ] Optimize image