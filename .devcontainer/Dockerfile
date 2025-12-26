FROM mcr.microsoft.com/devcontainers/base:ubuntu-24.04

RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
    && apt-get -y install --no-install-recommends python3 python3-pip python3-venv

RUN pip3 install --break-system-packages seaborn==0.9.0 pandas==1.5.3 matplotlib
