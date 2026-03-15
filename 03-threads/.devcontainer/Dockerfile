FROM ubuntu:latest
RUN apt-get update \
&& DEBIAN_FRONTEND=noninteractive apt-get install -yy --no-install-recommends \
 ripgrep \
 clang \
 build-essential \
 gdb \
 valgrind \
&& apt-get clean \
&& rm -rf /var/lib/apt/lists/*
