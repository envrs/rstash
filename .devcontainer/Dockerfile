# Devcontainer Dockerfile for Rust development
# Using a specific version for reproducibility, e.g., 1-bullseye. Check for the latest stable version.
FROM mcr.microsoft.com/devcontainers/rust:1-bullseye

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
