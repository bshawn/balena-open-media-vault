FROM debian:stable-slim

ENV DEBIAN_FRONTEND noninteractive

RUN apt-get update \
    && apt-get upgrade \
    && apt-get install -y --no-install-recommends sudo \
    && apt-get clean \
    && rm -rf /var/lib/apt/lists/*



RUN wget -O - https://github.com/OpenMediaVault-Plugin-Developers/installScript/raw/master/install | sudo bash

CMD [ "" ]
