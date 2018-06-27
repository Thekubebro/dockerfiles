FROM debian:buster
LABEL maintainer "Jessie Frazelle <colemanword@gmail.com>"

RUN apt-get update && apt-get install -y \
	nmap \
	--no-install-recommends \
	&& rm -rf /var/lib/apt/lists/*

ENTRYPOINT [ "nmap" ]
