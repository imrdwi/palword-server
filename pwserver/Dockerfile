FROM cm2network/steamcmd:latest AS pwserver

LABEL maintainer="rizki.k@pm.me"

COPY scripts /home/steam/scripts

RUN set -x \
  && steamcmd +runscript /home/steam/scripts/update_palworld.txt

EXPOSE 16261 16262 16263
