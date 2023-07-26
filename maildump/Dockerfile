FROM python:3.11-slim

RUN apt-get update
RUN pip install maildump

CMD ["maildump", "--http-ip", "0.0.0.0", "--smtp-ip", "0.0.0.0"]
