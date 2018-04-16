FROM alpine
ADD frps /frps
ADD frps.ini /frps.ini

EXPOSE 8088 4443 6000 7000 7500

ENTRYPOINT ["/frps","-c","/frps.ini"]