FROM alpine:3.10

COPY entrypoint.sh /entrypoint.sh
RUN apk add musl-dev gcc make g++ file

ENTRYPOINT [ "/entrypoint.sh" ]