FROM nginx:1.21.6-alpine

LABEL maintainer Richard Willis <willis.rh@gmail.com>
LABEL org.opencontainers.image.source https://github.com/badsyntax/docker
LABEL org.label-schema.name="base-nginx"
LABEL org.label-schema.description="Base nginx"
LABEL org.label-schema.vcs-url="https://github.com/badsyntax/docker"
LABEL org.label-schema.usage="README.md"
LABEL org.label-schema.vendor="badsyntax"

RUN adduser --system --no-create-home --shell /bin/false www-data -u 1000

COPY ./nginx /etc/nginx
