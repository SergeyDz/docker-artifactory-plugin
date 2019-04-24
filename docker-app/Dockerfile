# ---- Base Node ----
FROM alpine:3.8 AS base
# install node
RUN apk add --update --no-cache nodejs nodejs-npm tini
# set working directory
WORKDIR /root/bot
# Set tini as entrypoint
ENTRYPOINT ["/sbin/tini", "--"]