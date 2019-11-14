# FROM kong:1.4.0-alpine
FROM kong

RUN mkdir -p "/usr/local/kong/declarative"
COPY ./declarative/kong.yml /usr/local/kong/declarative/kong.yml
COPY ./config/kong.conf /etc/kong.conf

EXPOSE 8000 8443 8001 8444 9080 9081
