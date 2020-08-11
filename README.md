![Docker-Polaris](https://raw.githubusercontent.com/MephistoXoL/Docker-Polaris/master/Docker-Polaris.png)

# Docker-Polaris 
Latest Polaris Release MultiArch for Raspberry pi 4/3+/3/2, arm64 & amd64

[![Docker Pulls](https://img.shields.io/docker/pulls/mephistoxol/polaris?logo=docker)](https://hub.docker.com/r/mephistoxol/polaris)
[![Docker Image Version (tag latest semver)](https://img.shields.io/docker/v/mephistoxol/polaris/latest?logo=linux&logoColor=white)](https://hub.docker.com/r/mephistoxol/polaris)
[![MicroBadger Layers](https://img.shields.io/microbadger/layers/mephistoxol/polaris)](https://hub.docker.com/r/mephistoxol/polaris)
[![Docker Image Size (tag)](https://img.shields.io/docker/image-size/mephistoxol/polaris/latest)](https://hub.docker.com/r/mephistoxol/polaris)
[![Docker Stars](https://img.shields.io/docker/stars/mephistoxol/polaris)](https://hub.docker.com/r/mephistoxol/polaris)
[![Paypal](https://img.shields.io/badge/paypal-donate-orange?logo=paypal)](https://www.paypal.me/mephistoxol)

This image is the latest version of Fairwinds' Polaris, Dockerfile get and download the lastest release. (Based on alpine:latest)

Fairwinds' Polaris keeps your clusters sailing smoothly. It runs a variety of checks to ensure that Kubernetes pods and controllers are configured using best practices, helping you avoid problems in the future.

To use this image you should change it on the file ```dashboard.yaml```

You can download from ```kubectl apply -f https://github.com/FairwindsOps/polaris/releases/latest/download/dashboard.yaml```, then change image for ```mephistoxol/polaris:latest```

Polaris is powered by ```https://github.com/FairwindsOps/polaris```

## Install
Command line:
```
kubectl apply -f /your/path/for/dashboard.yaml
```

## Changelog
```
10-08-2020
- First Release
```

## Donate
[![Paypal](https://raw.githubusercontent.com/MephistoXoL/Things/master/paypal.png)](https://www.paypal.me/mephistoxol)

