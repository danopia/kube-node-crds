FROM hayd/alpine-deno:1.10.1
RUN apk add --no-cache smartmontools

ADD . /src/
RUN deno cache /src/loop/mod.ts
