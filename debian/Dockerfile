FROM debian:11.6-slim
RUN export DEBIAN_FRONTEND=noninteractive && \
 apt-get update && \
 apt-get -y install --no-install-recommends dnsutils && \
 apt-get clean && \
 rm -rf /var/lib/apt/lists/*
