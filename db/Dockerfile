FROM postgres:alpine3.16


ENV POSTGRES_PASSWORD p@ssw0rd42
ENV POSTGRES_DB postgres
ENV POSTGRES_USER postgres

EXPOSE 5432

 COPY db.sql /docker-entrypoint-initdb.d