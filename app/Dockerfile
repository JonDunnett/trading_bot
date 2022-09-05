FROM python:3.10

COPY requirements.txt /home/
RUN python -m pip install -r requirements.txt

RUN mkdir -p /home/src
COPY src/* /home/src/