# Image for libp11 + p11-kit integration testing

FROM fedora
MAINTAINER Anderson Sasaki

WORKDIR /test
ADD . /test

# Install packages
RUN dnf update -y && dnf install -y \
    libp11 \
    softhsm \
    gnutls-utils \
    procps \
    openssl \
    engine_pkcs11 \
    opensc

