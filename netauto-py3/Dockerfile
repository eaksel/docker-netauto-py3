FROM alpine:latest
LABEL maintainer="https://github.com/eaksel"
RUN apk add --no-cache build-base curl libffi-dev libxml2-dev libxslt-dev openssl-dev python3 python3-dev
RUN pip3 --no-cache-dir install --upgrade pip
RUN pip3 --no-cache-dir install ansible ipython napalm nornir
CMD ["sh"]