FROM postgres:11.1

MAINTAINER skoltun
COPY schema.sql /docker-entrypoint-initdb.d/
COPY data.sql /docker-entrypoint-initdb.d/