From python:3.9-slim-buster

WORKDIR /app/src

RUN mkdir -p /app/src/models

COPY requirements.txt /app/

RUN --mount=type=cache,target=/root/.cache/pip pip3 install -r /app/requirements.txt -i http://mirrors.cloud.aliyuncs.com/pypi/simple/ --trusted-host mirrors.cloud.aliyuncs.com

COPY . /app

EXPOSE 8000

CMD python3 main.py
