FROM gradiant/ueransim:3.2.6

RUN apt-get update && \
    apt-get install -y --no-install-recommends \
        tcpdump \
        iptables \
        net-tools && \
    apt-get clean && \
    rm -rf /var/lib/apt/lists/*

