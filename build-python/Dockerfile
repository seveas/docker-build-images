FROM seveas/build-debian-minimal

ARG DEBIAN_FRONTEND=noninteractive
RUN apt-get update && \
    apt-get -y install dh-python \
                       pypy        pypy-dev        pypy-setuptools    \
                       python-all  python-all-dev  python-setuptools  \
                       python3-all python3-all-dev python3-setuptools && \
    rm -r /var/cache/apt/archives /var/lib/apt/lists
