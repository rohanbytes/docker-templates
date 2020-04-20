FROM ubuntu
  
RUN \
    apt update && \
    apt install -y software-properties-common && \
    add-apt-repository -y ppa:deadsnakes/ppa && \
    apt install -y python3.7 && \
    update-alternatives --install /usr/bin/python python /usr/bin/python3.7 1
