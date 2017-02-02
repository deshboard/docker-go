FROM golang:1.7-alpine

RUN set -xe \
    && apk add --no-cache git \
    && apk add --no-cache --virtual .glide-deps \
        curl \
    && curl https://glide.sh/get | sh \
    && apk del .glide-deps
