# syntax=docker/dockerfile:1
FROM mcr.microsoft.com/devcontainers/rust:1

ARG USER=vscode
USER root

# Install some dependencies and zsh
RUN apt-get update && apt-get install -y --no-install-recommends \
    python3 python3-pip \
    texlive-latex-extra texlive-pictures texlive-science \
    zsh curl wget ca-certificates build-essential \
    && rm -rf /var/lib/apt/lists/*

# Use zsh as default shell
RUN usermod -s /usr/bin/zsh ${USER}

USER ${USER}
WORKDIR /home/${USER}

# Install mdBook and useful plugins
RUN cargo install mdbook \
    && cargo install mdbook-tera-backend \
    && cargo install i18n-report \
    && cargo install mdbook-i18n-helpers \
    && cargo install mdbook-mermaid

# Add completions
RUN echo 'eval "$(mdbook completions zsh)"' >> ~/.zshrc

EXPOSE 3000
