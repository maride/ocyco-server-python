# ocyco-server
API server for [OCYCO](https://github.com/opencyclecompass/) written in Python

Currently under development.

## Dependencies

Module | Version
---|---
Flask | >= 0.10.1
Flask_SQLAlchemy | >= 2.1
GeoAlchemy2 | >= 0.2.5
Shapely | >= 1.5.2
SQLAlchemy | >= 1.0.11
Werkzeug | >= 0.11.3

Install needed python modules, e.g. via *pip*:
```pip install flask flask_sqlalchemy sqlalchemy geoalchemy2 shapely psycopg2 werkzeug```.

You also need `postgresql`.

## Todo

- [ ] create tables upon start to ease first startup after installation and make `ocyco-server` production environment friendly.
- [ ] read database address from config file and/or parameter

## API
API documentation can be found [here](docs/API2.md)
