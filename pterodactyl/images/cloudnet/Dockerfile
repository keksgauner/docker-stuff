FROM azul/zulu-openjdk:17-jre-headless AS build

RUN         apt-get update -y \
            && apt-get install -y --no-install-recommends curl ca-certificates openssl git tar sqlite3 fontconfig libfreetype6 libstdc++6 lsof build-essential tzdata iproute2 locales jq \
            && apt-get clean \
            && rm -rf /var/lib/apt/lists/* \
            && adduser --disabled-password --home /home/container container \
            && locale-gen en_US.UTF-8

ENV         LC_ALL=en_US.UTF-8
ENV         LANG=en_US.UTF-8
ENV         LANGUAGE=en_US.UTF-8

USER        container
ENV         USER=container HOME=/home/container
WORKDIR     /home/container

COPY        entrypoint.sh /entrypoint.sh
ENTRYPOINT  [ "/bin/bash", "/entrypoint.sh" ]
