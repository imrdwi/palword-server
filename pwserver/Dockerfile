FROM cm2network/steamcmd:latest AS pwserver

LABEL maintainer="rizki.k@pm.me"

COPY scripts /home/steam/scripts

RUN set -x \
  && /home/steam/steamcmd/steamcmd.sh +runscript /home/steam/scripts/update_palworld.txt

EXPOSE 8211
