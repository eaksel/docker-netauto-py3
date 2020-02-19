FROM alpine:latest
LABEL maintainer="https://github.com/eaksel"
RUN apk add --no-cache build-base curl libffi-dev openssl-dev python3 python3-dev py3-lxml
RUN pip3 --no-cache-dir install --upgrade pip
RUN pip3 --no-cache-dir install ansible ipython netmiko napalm nornir
CMD ["sh"]