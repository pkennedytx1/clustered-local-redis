# M1 macs
FROM --platform=linux/amd64 redis:latest
# linux, windows, intel macs
# FROM redis:latest

COPY ./entrypoint.sh /entrypoint.sh
RUN chmod 755 /entrypoint.sh

ENTRYPOINT ["/entrypoint.sh"]