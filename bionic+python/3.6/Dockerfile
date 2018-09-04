FROM ubuntu:18.04
RUN apt update \
    && apt install -y --no-install-recommends python3 python3-pip \
    && ln -s /usr/bin/python3 /usr/bin/python \
    && ln -s /usr/bin/pip3 /usr/bin/pip \
    && rm -rf /var/lib/apt/lists/*

CMD ["/bin/bash"]
