FROM ubuntu:16.04

RUN apt-get update && \
	apt-get install -y --no-install-recommends \
	python3 \
	python3-pip \
    && rm -rf /var/lib/apt/lists/*

CMD ["python3"]

# crear la imagen
# docker build -t NOMBRE_IMAGEN:TAG .
