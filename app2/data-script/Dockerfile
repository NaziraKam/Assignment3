FROM alpine:latest
RUN apk update
RUN apk add mysql-client
WORKDIR /opt
COPY import.sh /opt
COPY mydatabase.sql /opt
CMD ./import.sh 

