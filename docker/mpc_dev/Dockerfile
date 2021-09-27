FROM node:16.3-alpine

RUN apk update && \
    apk add git

RUN yarn install

WORKDIR /tmp

RUN git clone https://github.com/multiparty/jiff.git

WORKDIR /mpc_dev
