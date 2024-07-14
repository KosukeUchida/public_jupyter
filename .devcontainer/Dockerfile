FROM python:3.12.4-slim

RUN apt-get update && \
    apt-get install -y gcc python3-dev && \
    pip install --upgrade pip

COPY requirements.txt /tmp/pip-tmp/

RUN pip install -r /tmp/pip-tmp/requirements.txt