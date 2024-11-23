FROM debian:bullseye

WORKDIR /data/mediamtx

COPY mediamtx mediamtx.yml /data/mediamtx/

RUN chmod +x /data/mediamtx/mediamtx

ENTRYPOINT ["/data/mediamtx/mediamtx"]