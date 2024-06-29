FROM python3.8-slim

WORKDIR /app

COPY requirements.txt .

RUN apt update && apt upgrade -y
RUN sudo apt install -y -r requirements.txt