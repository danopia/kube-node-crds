FROM hayd/alpine-deno:1.9.2
RUN apk add --no-cache smartmontools

ADD . /src/
RUN deno cache /src/loop/mod.ts
