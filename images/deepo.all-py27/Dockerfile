FROM ufoym/deepo:py27

RUN sed -i 's/archive.ubuntu.com/mirrors.ustc.edu.cn/g' /etc/apt/sources.list && \
    apt update && \
    apt install -y openssh-server openssh-client && \
    apt install opencv-python && \
    apt install easydict && \
    apt install shapely && \
    apt install swig && \
    apt-get clean && \
    apt-get autoremove && \
