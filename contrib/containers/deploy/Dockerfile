FROM phusion/baseimage:focal-1.0.0
LABEL maintainer="NeonX Developers <dev@neonx.org>"
LABEL description="Dockerised NeonX, built from Travis"

ARG USER_ID
ARG GROUP_ID

ENV HOME /home/neonx

# add user with specified (or default) user/group ids
ENV USER_ID ${USER_ID:-1000}
ENV GROUP_ID ${GROUP_ID:-1000}
RUN groupadd -g ${GROUP_ID} neonx && \
    useradd -u ${USER_ID} -g neonx -s /bin/bash -m -d /home/neonx neonx && \
    mkdir /home/neonx/.neonx && \
    chown ${USER_ID}:${GROUP_ID} -R /home/neonx

COPY bin/* /usr/local/bin/

RUN chmod a+x /usr/local/bin/*

USER neonx

VOLUME ["/home/neonx"]

EXPOSE 18069 9999 28069 28070

WORKDIR /home/neonx
