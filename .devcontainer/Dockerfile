FROM node:22-alpine

RUN set -eux -o pipefail && \
    apk add --no-check-certificate --no-cache --update git

RUN npm config set strict-ssl false
RUN yarn config set strict-ssl false --global
RUN git config --global http.sslVerify false
