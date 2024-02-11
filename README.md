Syslog Service for Networking Labs
==================================

A simple Syslog service for networking labs. The service uses [RSyslog][RSyslog].

[RSyslog]: https://www.rsyslog.com/

Basic Usage
-----------

Start the service:

```sh
docker compose up --detach
```

Print logs:

```sh
docker compose logs
```

Stop the service:

```sh
docker compose down
```

Testing
-------

```sh
logger --server=localhost "hello world"
```
