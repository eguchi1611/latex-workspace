FROM mcr.microsoft.com/devcontainers/base@sha256:9d6a94355ab4f6c9597ee802b9d1ead37e6a76cad3685bf62123d2ebf624ea75

RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
  && apt-get -y install --no-install-recommends texlive-full

COPY .latexmkrc /home/vscode/.latexmkrc