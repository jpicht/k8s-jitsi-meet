ARG JITSI_REPO=jitsi
ARG DOCKER_IMAGE_PREFIX=jitsi-k8s-
FROM ${JITSI_REPO}/${DOCKER_IMAGE_PREFIX}base-java

RUN \
	apt-dpkg-wrap apt-get update && \
	apt-dpkg-wrap apt-get install -y jicofo && \
	apt-cleanup

COPY rootfs/ /

VOLUME /config

