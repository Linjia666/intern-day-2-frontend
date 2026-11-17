FROM python:3.12-slim-bookworm

RUN pip install --no-cache-dir uv -i https://pypi.tuna.tsinghua.edu.cn/simple

RUN apt-get update && apt-get install -y git \
    && rm -rf /var/lib/apt/lists/*

WORKDIR /workspace
