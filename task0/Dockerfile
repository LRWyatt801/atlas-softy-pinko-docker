FROM ubuntu:latest

COPY --chmod=1 print.sh /app/

WORKDIR /app

RUN apt-get update
RUN apt-get upgrade -y

ENTRYPOINT [ "./print.sh" ]
