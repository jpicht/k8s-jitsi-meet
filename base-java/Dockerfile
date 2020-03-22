ARG JITSI_REPO=jpicht
ARG DOCKER_IMAGE_PREFIX=jitsi-k8s-
FROM ${JITSI_REPO}/${DOCKER_IMAGE_PREFIX}base

RUN	\
	mkdir -p /usr/share/man/man1 && \
	apt-dpkg-wrap apt-get update && \
	apt-dpkg-wrap apt-get install -y openjdk-8-jre-headless && \
	apt-cleanup

