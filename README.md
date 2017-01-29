Rename .env.dist to .env, populate with correct values.

1. Go to url and create admin
1. Create tfws user for writing data.

Usernames and passwords below are just examples.

# Grafana Configuration
1. Add data source
1. See screenshot of example settings.


# InfluxDb Configuration TFWS

1. Go to url and create admin!
1. `CREATE DATABASE "highgarden"`
1. `CREATE USER tfws WITH PASSWORD 'tfws'`
1. `GRANT ALL ON highgarden TO tfws`


# InfluxDb Configuration Nest
1. `CREATE USER nest' WITH PASSWORD 'nest'`
1. `GRANT ALL ON highgarden TO nest`

# Import Dashboard

1. Import from json file located in /docs, note your db name is probably not 'highgarden' so ymmv :)

