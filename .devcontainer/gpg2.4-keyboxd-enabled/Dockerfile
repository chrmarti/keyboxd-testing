FROM mcr.microsoft.com/devcontainers/base:noble

USER vscode
RUN mkdir -p -m 700 ~/.gnupg && echo "use-keyboxd" >> ~/.gnupg/common.conf
USER root
