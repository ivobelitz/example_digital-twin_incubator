FROM quay.io/influxdb/influxdb:v2.0.3

COPY ./config.yaml /config.yaml

RUN /entrypoint.sh

CMD influxd