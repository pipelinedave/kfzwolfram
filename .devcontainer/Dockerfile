FROM mcr.microsoft.com/vscode/devcontainers/javascript-node:0-18

RUN apt-get update && apt-get install -y \
    curl \
    git \
    && rm -rf /var/lib/apt/lists/*

WORKDIR /workspace

# EXPOSE 3000
