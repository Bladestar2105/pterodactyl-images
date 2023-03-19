# Images

This repository contains a bunch of images designed for use with Pterodactyl's egg system.  Each image is rebuilt
periodically to ensure dependencies are always up-to-date.

Images are hosted on `ghcr.io`.

To use any of these images, use `ghcr.io/bladestar2105/pterodactyl-images:<IMAGE>`.

Any images ending with `-install` should only be used as a install image for running an install script, these images
will not work to run the actual server and are only designed to reduce installation time and network usage by
pre-installing common installation dependencies such as `curl` and `wget`.

## Available Images

### Games

- [`source`](https://github.com/bladestar2105/pterodactyl-images/tree/master/games/source)
  - Image specifically designed for running Source Engine servers.
  - Tags
    - `ghcr.io/bladestar2105/pterodactyl-images:source`
  - Supported Architectures
    - `linux/amd64`

### Generic

- [`alpine`](https://github.com/bladestar2105/pterodactyl-images/tree/master/generic/alpine)
  - Generic [Alpine](https://alpinelinux.org) Linux image
  - Tags
    - `ghcr.io/bladestar2105/pterodactyl-images:alpine`
  - Supported Architectures
    - `linux/amd64`
    - `linux/arm64`
- [`debian`](https://github.com/bladestar2105/pterodactyl-images/tree/master/generic/debian)
  - Generic [Debian](https://www.debian.org/) image
  - Tags
    - `ghcr.io/bladestar2105/pterodactyl-images:debian`
  - Supported Architectures
    - `linux/amd64`
    - `linux/arm64`
- [`ubi`](https://github.com/bladestar2105/pterodactyl-images/tree/master/generic/ubi)
  - Generic [RedHat UBI](https://developers.redhat.com/products/rhel/ubi) image
  - Tags
    - `ghcr.io/bladestar2105/pterodactyl-images:ubi`
  - Supported Architectures
    - `linux/amd64`
    - `linux/arm64`

### Golang

- [`go1.17`](https://github.com/bladestar2105/pterodactyl-images/tree/master/go/1.17)
  - Tags
    - `ghcr.io/bladestar2105/pterodactyl-images:go1.17`
  - Supported Architectures
    - `linux/amd64`
    - `linux/arm64`
- [`go1.18`](https://github.com/bladestar2105/pterodactyl-images/tree/master/go/1.18)
  - Tags
    - `ghcr.io/bladestar2105/pterodactyl-images:go1.18`
  - Supported Architectures
    - `linux/amd64`
    - `linux/arm64`
- [`go1.19`](https://github.com/bladestar2105/pterodactyl-images/tree/master/go/1.19)
  - Tags
    - `ghcr.io/bladestar2105/pterodactyl-images:go1.19`
  - Supported Architectures
    - `linux/amd64`
    - `linux/arm64`

### Java

#### Java 8

- [`java8`](https://github.com/bladestar2105/pterodactyl-images/tree/master/java/8)
  - Tags
    - `ghcr.io/bladestar2105/pterodactyl-images:java8`
  - Supported Architectures
    - `linux/amd64`
  - End of life: `December 2030`
- [`java8-zulu`](https://github.com/bladestar2105/pterodactyl-images/tree/master/java/8-zulu)
  - Tags
    - `ghcr.io/bladestar2105/pterodactyl-images:java8-zulu`
  - Supported Architectures
    - `linux/amd64`
    - `linux/arm64`
  - End of life: `December 2030`

#### Java 11

- [`java11-hotspot`](https://github.com/bladestar2105/pterodactyl-images/tree/master/java/11-hotspot)
  - Tags
    - `ghcr.io/bladestar2105/pterodactyl-images:java11-hotspot`
  - Supported Architectures
    - `linux/amd64`
    - `linux/arm64`
  - End of life: `September 2026`
- [`java11-zulu`](https://github.com/bladestar2105/pterodactyl-images/tree/master/java/11-zulu)
  - Tags
    - `ghcr.io/bladestar2105/pterodactyl-images:java11-zulu`
  - Supported Architectures
    - `linux/amd64`
    - `linux/arm64`
  - End of life: `September 2026`

#### Java 17

- [`java17-zulu`](https://github.com/bladestar2105/pterodactyl-images/tree/master/java/17-zulu)
  - Tags
    - `ghcr.io/bladestar2105/pterodactyl-images:java17-zulu`
  - Supported Architectures
    - `linux/amd64`
    - `linux/arm64`
  - End of life: `September 2029`

#### Java 18

- [`java18-zulu`](https://github.com/bladestar2105/pterodactyl-images/tree/master/java/18-zulu)
  - Tags
    - `ghcr.io/bladestar2105/pterodactyl-images:java18-zulu`
  - Supported Architectures
    - `linux/amd64`
    - `linux/arm64`
  - End of life: `September 2022`

#### Java 19

- [`java19-zulu`](https://github.com/bladestar2105/pterodactyl-images/tree/master/java/19-zulu)
  - Tags
    - `ghcr.io/bladestar2105/pterodactyl-images:java19-zulu`
  - Supported Architectures
    - `linux/amd64`
    - `linux/arm64`
  - End of life: `March 2023`

### Node.js

- [`node14`](https://github.com/bladestar2105/pterodactyl-images/tree/master/node/14)
  - <https://catalog.redhat.com/software/containers/ubi8/nodejs-14-minimal/6065b8e1b92fbda3a4c65d91>
  - Tags
    - `ghcr.io/bladestar2105/pterodactyl-images:node14`
  - Supported Architectures
    - `linux/amd64`
    - `linux/arm64`
  - End of life: `April 2023`
- [`node16`](https://github.com/bladestar2105/pterodactyl-images/tree/master/node/16)
  - <https://catalog.redhat.com/software/containers/ubi9/nodejs-16-minimal/61a6059abfd4a5234d59621f>
  - Tags
    - `ghcr.io/bladestar2105/pterodactyl-images:node16`
  - Supported Architectures
    - `linux/amd64`
    - `linux/arm64`
  - End of life: `September 2023`
- [`node18`](https://github.com/bladestar2105/pterodactyl-images/tree/master/node/18)
  - <https://catalog.redhat.com/software/containers/ubi9/nodejs-18-minimal/62e8e919d4f57d92a9dee838>
  - Tags
    - `ghcr.io/bladestar2105/pterodactyl-images:node18`
  - Supported Architectures
    - `linux/amd64`
    - `linux/arm64`
  - End of life: `April 2025`

### Python

- [`python3.7`](https://github.com/bladestar2105/pterodactyl-images/tree/master/python/3.7)
  - Tags
    - `ghcr.io/bladestar2105/pterodactyl-images:python3.7`
  - Supported Architectures
    - `linux/amd64`
    - `linux/arm64`
- [`python3.8`](https://github.com/bladestar2105/pterodactyl-images/tree/master/python/3.8)
  - Tags
    - `ghcr.io/bladestar2105/pterodactyl-images:python3.8`
  - Supported Architectures
    - `linux/amd64`
    - `linux/arm64`
- [`python3.9`](https://github.com/bladestar2105/pterodactyl-images/tree/master/python/3.9)
  - Tags
    - `ghcr.io/bladestar2105/pterodactyl-images:python3.9`
  - Supported Architectures
    - `linux/amd64`
    - `linux/arm64`
- [`python3.10`](https://github.com/bladestar2105/pterodactyl-images/tree/master/python/3.10)
  - Tags
    - `ghcr.io/bladestar2105/pterodactyl-images:python3.10`
  - Supported Architectures
    - `linux/amd64`
    - `linux/arm64`
- [`python3.11`](https://github.com/bladestar2105/pterodactyl-images/tree/master/python/3.11)
  - Tags
    - `ghcr.io/bladestar2105/pterodactyl-images:python3.11`
  - Supported Architectures
    - `linux/amd64`
    - `linux/arm64`

### Installers

- [`alpine-install`](https://github.com/bladestar2105/pterodactyl-images/tree/master/installers/alpine)
  - Tags
    - `ghcr.io/bladestar2105/pterodactyl-images:alpine-install`
  - Supported Architectures
    - `linux/amd64`
    - `linux/arm64`
- [`debian-install`](https://github.com/bladestar2105/pterodactyl-images/tree/master/installers/debian)
  - Tags
    - `ghcr.io/bladestar2105/pterodactyl-images:debian-install`
  - Supported Architectures
    - `linux/amd64`
    - `linux/arm64`
- [`source-install`](https://github.com/bladestar2105/pterodactyl-images/tree/master/installers/source)
  - Tags
    - `ghcr.io/bladestar2105/pterodactyl-images:source-install`
  - Supported Architectures
    - `linux/amd64`
- [`ubi-install`](https://github.com/bladestar2105/pterodactyl-images/tree/master/installers/ubi)
  - Tags
    - `ghcr.io/bladestar2105/pterodactyl-images:ubi-install`
  - Supported Architectures
    - `linux/amd64`
    - `linux/arm64`
