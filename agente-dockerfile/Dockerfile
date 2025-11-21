FROM jenkins/inbound-agent:latest

USER root

RUN apt-get update && \
    apt-get install -y docker.io procps && \
    apt-get clean

USER root
