FROM debian:stable

ARG DEBIAN_FRONTEND=noninteractive
RUN apt-get update && \
    apt-get -y install devscripts git build-essential && \
    rm -r /var/cache/apt/archives /var/lib/apt/lists
