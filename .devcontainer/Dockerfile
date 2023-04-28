FROM 	mcr.microsoft.com/vscode/devcontainers/rust

# Install `protoc`
RUN apt-get update && \
    DEBIAN_FRONTEND=noninteractive apt-get -y install protobuf-compiler && \
    rm -rf /var/lib/apt/lists/*
