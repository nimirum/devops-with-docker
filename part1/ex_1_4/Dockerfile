# ex_1_4
FROM ubuntu
RUN apt-get update && apt-get install -y curl
WORKDIR /app
COPY curler.sh ./
RUN chmod a+x curler.sh
CMD ["/app/curler.sh"]
