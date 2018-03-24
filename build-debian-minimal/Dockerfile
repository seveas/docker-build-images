FROM debian:stable

ARG DEBIAN_FRONTEND=noninteractive
RUN cp /etc/apt/sources.list /tmp && \
    sed -e 's/^deb/deb-src/' /tmp/sources.list >> /etc/apt/sources.list && \
    rm /tmp/sources.list && \
    apt-get update && \
    apt-get -y install devscripts debhelper git build-essential && \
    rm -r /var/cache/apt/archives /var/lib/apt/lists
