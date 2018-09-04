FROM odacharlee/python:3.6-bionic

RUN apt update \
    && apt install -y --no-install-recommends net-tools iputils-ping dnsutils python3-dev git wget curl vim \
    && rm -rf /var/lib/apt/lists/*

CMD ["/bin/bash"]
