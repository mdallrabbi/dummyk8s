FROM nginx:1.23.3-alpine-slim

RUN rm /etc/nginx/conf.d/default.conf
COPY nginx-old.conf /etc/nginx/conf.d

WORKDIR /usr/src/app