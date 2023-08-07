# syntax=docker/dockerfile:1.4


# Base Image
# =============================================================================

# Use the official Docker Node.js image as a base. This includes Node.js and npm.
FROM node:16

# Avoid warnings by switching to noninteractive. This is important when installing packages that ask for input during installation.
ENV DEBIAN_FRONTEND=noninteractive

# Install the Ethereum development tools, Truffle and Ganache-CLI. Truffle is a development environment, testing framework and asset pipeline for Ethereum. Ganache-CLI, part of the Truffle suite, allows you to create a private Ethereum blockchain for testing purposes.
RUN npm install -g truffle ganache-cli

# Install the Decentraland SDK. This SDK is necessary for creating experiences within Decentraland.
RUN npm install -g decentraland

# Switch back to dialog for any ad-hoc use of apt-get. This means that if you run apt-get manually in the future, it will behave as normal.
ENV DEBIAN_FRONTEND=dialog

# Set the default shell to bash rather than sh. bash is a more powerful shell and this can be useful for running scripts and debugging.
ENV SHELL /bin/bash
