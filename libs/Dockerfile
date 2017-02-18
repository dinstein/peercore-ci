FROM ubuntu:xenial
MAINTAINER Linfeng Liang <lianglinfeng@gmail.com>

ENV HOME /build

RUN apt-get update && apt-get install -y --no-install-recommends \
    autoconf automake autopoint \
    build-essential byacc \
    ca-certificates cmake curl \
    git gperf gtk-doc-tools \
    libffi-dev libpcre3-dev libmount-dev \
    pkg-config \
    texinfo \
    unzip \
    wget \
    zlib1g-dev

# RUN apt-get clean && rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/*

WORKDIR /build
