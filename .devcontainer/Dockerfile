# FROM mcr.microsoft.com/oryx/build:vso-focal-20220120.1 as kitchensink
FROM mcr.microsoft.com/vscode/devcontainers/base:debian-11 

COPY first-run-notice.txt /tmp/scripts/
RUN mkdir -p /usr/local/etc/vscode-dev-containers/ \
 && mv -f /tmp/scripts/first-run-notice.txt /usr/local/etc/vscode-dev-containers/