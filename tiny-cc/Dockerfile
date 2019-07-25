FROM alpine:edge

ENV LD_LIBRARY_PATH "/opt/lib:/usr/local/lib:/usr/lib:/lib"
ENV LIBRARY_PATH "/opt/lib:/usr/local/lib:/usr/lib:/lib"

RUN apk update && apk add --no-cache -X http://dl-cdn.alpinelinux.org/alpine/edge/testing musl-dev make cmake tcc
