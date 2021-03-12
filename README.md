# Mercure

Mercure is an open protocol for real-time communications designed to be fast, reliable and battery-efficient. It is a modern and convenient replacement for both the Websocket API and the higher-level libraries and services relying on it.

https://mercure.rocks/

## Installation

Copy file `.env.example` to `.env`.

Edit `.env` file und update the following required parameters:

```
MERCURE_PUBLISHER_JWT_KEY=
MERCURE_SUBSCRIBER_JWT_KEY=
```

In order to install and start Mercure server via `docker-compose`, run the following command:

```
docker-compose up -d --build
```

## Configurations

Exposed ports: 

* HTTP - 1337
* HTTPS - 1338

More details related to configurations, available here https://mercure.rocks/docs
