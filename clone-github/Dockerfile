FROM alpine

RUN apk update
RUN apk add git

COPY ./clone /usr/local/clone

ENTRYPOINT ["/usr/local/clone"]

