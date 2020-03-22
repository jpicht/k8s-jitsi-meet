# Jitsi Meet on Kubernetes (via Helm)

[Jitsi] is a set of Open Source projects that allows you to easily build and deploy secure videoconferencing solutions.

[Jitsi Meet] is a fully encrypted, 100% Open Source videoconferencing solution that you can use all day, every day, for free — with no account needed.

This repository contains the necessary tools to run a Jitsi Meet stack on [Kubernetes] using [Helm].

## Table of contents

* [Quick start](#quick-start)

<hr />

## Quick start

Create a values file based on values.yaml and install the chart using helm.

```
cd k8s
cp values.yaml your-values.yaml
helm install -f your-values.yaml your-installation-nickname .
```


## Links

[Jitsi]: https://jitsi.org/
[Jitsi Meet]: https://jitsi.org/jitsi-meet/
[S6 Overlay]: https://github.com/just-containers/s6-overlay
[Jitsi repositories]: https://jitsi.org/downloads/
[Prosody]: https://prosody.im/
[Jicofo]: https://github.com/jitsi/jicofo
[Jitsi Videobridge]: https://github.com/jitsi/jitsi-videobridge
[Jigasi]: https://github.com/jitsi/jigasi
[ICE]: https://en.wikipedia.org/wiki/Interactive_Connectivity_Establishment
[STUN]: https://en.wikipedia.org/wiki/STUN
[jwt.io]: https://jwt.io/#debugger-io
[Etherpad]: https://github.com/ether/etherpad-lite
[Jibri]: https://github.com/jitsi/jibri
