FROM alpine:3.10

COPY entrypoint.sh /entrypoint.sh

RUN chmode +x entrypoint.sh

ENTRYPOINT ["/entrypoint.sh"]
