FROM debian:buster-slim
LABEL maintainer="Daniel Zeltner <daniel.zeltner@outlook.com>"
LABEL version="20190923"

RUN apt-get update \
    && apt-get install -y biber latexmk make texlive-full \
    && apt-get autoclean \
    && apt-get clean \
    && rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/*

