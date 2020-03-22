ARG JITSI_REPO=jitsi
ARG DOCKER_IMAGE_PREFIX=jitsi-k8s-
FROM ${JITSI_REPO}/${DOCKER_IMAGE_PREFIX}base

RUN \
	apt-dpkg-wrap apt-get update && \
	apt-dpkg-wrap apt-get install -y nginx-extras jitsi-meet-web && \
	apt-cleanup && \
	rm -f /etc/nginx/conf.d/default.conf && \
	rm -f /usr/share/jitsi-meet/interface_config.js

COPY rootfs/ /

EXPOSE 80
