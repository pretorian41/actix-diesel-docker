FROM rust

WORKDIR /rust

COPY . /rust

RUN cargo install diesel_cli
RUN rustup component add rustfmt
RUN rustup component add clippy
RUN cargo build