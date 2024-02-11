FROM debian:bookworm-20240130-slim

RUN apt-get update && \
    apt-get --yes install \
        rsyslog

COPY rsyslog.conf /etc/rsyslog.conf

ENTRYPOINT ["rsyslogd", "-n"]

EXPOSE 514/udp
