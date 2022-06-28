FROM alpine:latest
RUN apk --no-cache add curl
CMD echo "$(date '+%d/%m/%Y %H:%M:%S') -> Should call the API here "
# CMD curl -s https://api.coindesk.com/v1/bpi/currentprice.json