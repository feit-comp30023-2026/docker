# Adapted from https://github.com/devcontainers/images/blob/main/src/cpp/.devcontainer/Dockerfile
FROM rust:1-bookworm

RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
    && apt-get -y install build-essential valgrind clang lldb llvm gdb \
        make git vim curl wget ca-certificates ripgrep xxd nasm strace hyperfine net-tools \
    && apt-get autoremove -y \
    && apt-get clean -y \
    && rm -rf /var/lib/apt/lists/*
