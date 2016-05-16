FROM gcr.io/google_containers/ubuntu-slim:0.2
COPY ./bin/boot /bin/boot
RUN apt-get update && apt-get -y install ca-certificates && apt-get clean
EXPOSE 8080
CMD ["/bin/boot"]
