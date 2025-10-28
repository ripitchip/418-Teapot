# syntax=docker/dockerfile:1
FROM mcr.microsoft.com/devcontainers/base:ubuntu

ARG USER=vscode
ARG DEBIAN_FRONTEND=noninteractive

# Use zsh for a better shell experience
RUN usermod -s /usr/bin/zsh ${USER}

# Install dependencies for Rust and mdBook
RUN apt-get update && apt-get install -y --no-install-recommends \
    curl wget ca-certificates build-essential zsh \
    && rm -rf /var/lib/apt/lists/*

USER ${USER}
WORKDIR /home/${USER}

# Add mdBook completions to zsh
RUN echo 'eval "$(mdbook completions zsh)"' >> ~/.zshrc

EXPOSE 3000
