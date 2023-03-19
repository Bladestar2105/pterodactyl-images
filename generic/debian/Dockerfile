#
# Copyright (c) 2023 Bladestar2105
#
# Permission is hereby granted, free of charge, to any person obtaining a copy
# of this software and associated documentation files (the "Software"), to deal
# in the Software without restriction, including without limitation the rights
# to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
# copies of the Software, and to permit persons to whom the Software is
# furnished to do so, subject to the following conditions:
#
# The above copyright notice and this permission notice shall be included in all
# copies or substantial portions of the Software.
#
# THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
# IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
# FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
# AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
# LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
# OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
# SOFTWARE.
#

FROM		--platform=$TARGETOS/$TARGETARCH docker.io/library/debian:stable-slim

LABEL		author="Bladestar2105" maintainer="stelios@sakalis.eu"

LABEL		org.opencontainers.image.source="https://github.com/Bladestar2105/pterodactyl-images"
LABEL		org.opencontainers.image.licenses=MIT

RUN			apt-get update -y && apt-get upgrade -y && apt-get install -y unzip wget build-essential doxygen graphviz libspatialindex-dev postgresql-server-dev-all libirrlicht-dev cmake libbz2-dev libjpeg-dev libxxf86vm-dev libsqlite3-dev libopenal-dev libcurl4-gnutls-dev libfreetype6-dev zlib1g-dev libgmp-dev libjsoncpp-dev luajit libluajit-5.1-dev libncurses5-dev libzstd-dev ca-certificates iproute2 tzdata \
				&& adduser -D -h /home/container container

USER		container
ENV			USER=container HOME=/home/container
WORKDIR		/home/container

COPY		./entrypoint.sh /entrypoint.sh
CMD			[ "/bin/bash", "/entrypoint.sh" ]
