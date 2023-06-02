# Simple configuration for Elastic and Kibana

Provides docker compose configuration to run Elastic and Kibana.

Uses the `es_data` volume to persist Elastic data.

# Dependencies

Make sure to install:

  * docker
  * docker-compose

# Usage

Before running the first time, create an empty directory `es_data`.

To start:

``` shell
docker compose up -d
```

To bring everything down, removing the containers entirely:

``` shell
docker compose down
```

