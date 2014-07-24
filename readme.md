# Sentry
Exception tracking and error logging

* `docker build -t sentry .`
* `docker run sentry`

Ports

* 9000
* 9001/udp

Environment

* `DB_ENGINE`: Type of database engine (i.e. mysql, sqlite3, postgresql_psycopg2)
* `DB_NAME`: Database name
* `DB_USER`: Database user
* `DB_PASSWORD`: Database password
* `DB_HOST`: Database host
* `DB_PORT`: Database port
* `CACHE_ENDPOINT`: Memcached endpoint (i.e. 127.0.0.1:11211)
* `SENTRY_URL`: Sentry application url
* `SECRET_KEY`: Application secret key (make sure to set this!)
