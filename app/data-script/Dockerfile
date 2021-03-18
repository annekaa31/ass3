FROM alpine
RUN apk update && apk add mysql-client
WORKDIR /opt
COPY import.sh .
COPY mydatabase.sql .
CMD ./import.sh