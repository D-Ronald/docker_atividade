
FROM ubuntu:22.04

WORKDIR /app

RUN apt-get update && \
    apt-get install -y python3 python3-pip && \
    apt-get clean

COPY process.py /app/process.py

CMD ["python3", "process.py"]
