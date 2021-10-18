FROM mysql:5.7

COPY ./schema.sql.gz /docker-entrypoint-initdb.d/schema.sql.gz
COPY ./yourls.sql.gz /docker-entrypoint-initdb.d/yourls.sql.gz
