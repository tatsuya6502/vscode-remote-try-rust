FROM mcr.microsoft.com/vscode/devcontainers/rust:1

# [Optional] Uncomment this section to install additional packages.
# RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
#     && apt-get -y install --no-install-recommends <your-package-list-here>

# Install some Cargo sub-commands.
RUN cargo install cargo-bloat && \
    cargo install cargo-edit && \
    cargo install cargo-expand && \
    cargo install cargo-licence && \
    cargo install cargo-outdated && \
    cargo install cargo-upgrade
