FROM arm32v7/debian
RUN apt-get update && apt install -y -q dnsmasq
EXPOSE 53/udp
VOLUME /etc/hosts
VOLUME /etc/resolv.conf
VOLUME /etc/dnsmasq.conf
ENTRYPOINT ["dnsmasq","--no-daemon"]
