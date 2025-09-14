# Devcontainer Dockerfile for Rust development
FROM mcr.microsoft.com/devcontainers/rust:latest

# Install additional packages if needed
RUN apt-get update && \
    apt-get install -y --no-install-recommends \
    build-essential \
    pkg-config \
    libssl-dev \
    ca-certificates \
    curl \
    git \
    && rm -rf /var/lib/apt/lists/*

# Set up any environment variables or additional configuration below
