# HackersHub-Docker Dockerfile for testing purpose

FROM nginx:1.17-alpine

RUN apk update && apk upgrade && \
    apk add --no-cache bash git

WORKDIR /usr/share/nginx/html

RUN rm * \
    && git clone https://github.com/Hackers-Hub/HackersHub.git .
