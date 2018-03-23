FROM debian:stable

ARG DEBIAN_FRONTEND=noninteractive
RUN apt-get update && \
    apt-get -y install git build-essential && \
    apt-get -y build-dep git &&
    rm -r /var/cache/apt/archives /var/lib/apt/lists
