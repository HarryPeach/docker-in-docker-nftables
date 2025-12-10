# Docker-in-Docker Devcontainer Feature with nftables support

Docker [recently enabled nftables support](https://docs.docker.com/engine/network/firewall-nftables/), but if you use docker-in-docker you also will need this enabled on the nested docker instance too.


This repo provides a devcontainer feature that patches the docker-in-docker default feature to add a flag to enable nftables support. Please note, that you'll also need to specify the latest version of Docker (29+).