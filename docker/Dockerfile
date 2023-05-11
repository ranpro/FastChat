FROM nvidia/cuda:12.0.0-runtime-ubuntu22.04

RUN apt update -y \
    && apt install -y python3 python3-pip \
    && pip3 install fschat==0.2.7 \
    && pip3 install cpm_kernels
