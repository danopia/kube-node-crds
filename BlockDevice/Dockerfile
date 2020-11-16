FROM hayd/alpine-deno

RUN apk add --no-cache smartmontools

ADD . /src/
RUN deno cache /src/loop/mod.ts
