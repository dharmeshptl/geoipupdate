FROM alpine:3.11.5

COPY geoipupdate /usr/bin/geoipupdate
COPY docker/entry.sh /usr/bin/entry.sh

ENTRYPOINT ["/usr/bin/entry.sh"]

VOLUME [ "/usr/share/GeoIP" ]
