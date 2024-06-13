FROM ghcr.io/analogj/scrutiny:master-collector
WORKDIR /

ENV COLLECTOR_API_ENDPOINT=192.168.1.126:8083 \
    COLLECTOR_CRON_SCHEDULE="*/10 * * * *" \
    COLLECTOR_HOST_ID=jollylife_ha

VOLUME [ "/run/udev" ]
