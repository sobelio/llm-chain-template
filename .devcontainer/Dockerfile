FROM mcr.microsoft.com/devcontainers/rust:0-1-bullseye

# Install `protoc`
RUN /usr/bin/bash -c "export DEBIAN_FRONTEND=noninteractive && apt update && apt -y install protobuf-compiler"
