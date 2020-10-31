FROM ubuntu:18.04

LABEL mantainer="pgraffigna"

RUN apt-get update && apt-get install -y \
	firefox \
	--no-install-recommends \
	&& rm -rf /var/lib/apt/lists/*

CMD ["/usr/bin/firefox"]

# ip pública
# export DISPLAY=$(curl -s ifconfig.me):0

# ip localhost WSL
# export DISPLAY=$(grep -m 1 nameserver /etc/resolv.conf | awk '{print $2}'):0 

# ip localhost Windows
# export DISPLAY=ipconfig:0

# ejecutar contenedor
# docker run --name firefox -e DISPLAY=$DISPLAY IMAGEN

