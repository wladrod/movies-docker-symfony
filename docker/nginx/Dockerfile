FROM nginx:1.26

ARG UID

RUN adduser -u ${UID} --disabled-password --gecos "" appuser

COPY default.conf /etc/nginx/conf.d/
