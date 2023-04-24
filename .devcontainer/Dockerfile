FROM mcr.microsoft.com/devcontainers/rust:0-1-bullseye

# Install `protoc`
RUN export DEBIAN_FRONTEND=noninteractive && apt update &&  \
    && apt -y install protobuf-compiler
