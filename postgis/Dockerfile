ARG BASE_IMAGE=registry.teco.edu/smartaqnet/timescaledb-postgis:1.6.1-pg11-oss
FROM $BASE_IMAGE
# copy init script so it will run automatically after startup
COPY ./smartaqnet_init_db.sh /docker-entrypoint-initdb.d/