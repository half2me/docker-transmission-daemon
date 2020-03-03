FROM alpine

RUN apk --no-cache add \
    transmission-daemon

VOLUME ["/var/lib/transmission"]

EXPOSE 9091 51413/tcp 51413/udp
CMD ["transmission-daemon"]