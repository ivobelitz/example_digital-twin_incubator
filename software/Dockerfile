from python:3.11-slim

# Install dependencies
RUN apt-get update && \
    apt-get install -y python3-pip
WORKDIR /app
COPY . /app
RUN pip install -r requirements.txt
CMD ["python3", "-m", "startup.start_all_services"]