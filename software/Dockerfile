FROM python:3.11-slim

COPY . /

RUN apt update && apt install -y python3-pip
RUN pip install -r requirements.txt

CMD python3 -m startup.start_all_services