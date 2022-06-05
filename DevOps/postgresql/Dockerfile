FROM postgres:latest

ENV POSTGRES_USER=postgres
ENV POSTGRES_PASSWORD=root

COPY orders.sql /docker-entrypoint-initdb.d/
COPY people.sql /docker-entrypoint-initdb.d/
COPY returns.sql /docker-entrypoint-initdb.d/