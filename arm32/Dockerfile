FROM arm32v7/debian
RUN apt-get update && apt install -y -q dnsmasq
EXPOSE 53/udp
ENTRYPOINT ["dnsmasq","--no-daemon","--log-queries"]
