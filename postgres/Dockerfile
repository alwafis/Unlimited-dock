FROM postgres:latest

RUN apt-get update \
  && apt-get install -y postgresql-9.4-postgis-2.1 postgis \
  && rm -rf /var/lib/apt/lists/*
