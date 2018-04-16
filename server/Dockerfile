FROM alpine
ADD frps /frps
ADD frps.ini /frps.ini

EXPOSE 80 443 6000 7000 7500

ENTRYPOINT ["/frps","-c","/frps.ini"]