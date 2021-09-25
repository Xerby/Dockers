FROM debian:buster


RUN set -xe \
    && apt-get update \
    && apt-get install -y dante-server

COPY ./run /usr/local/sbin

EXPOSE 1080

CMD run