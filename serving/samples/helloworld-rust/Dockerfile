FROM rust:1.27.0

WORKDIR /usr/src/app
COPY . .

RUN cargo install

EXPOSE 8080

CMD ["hellorust"]