# Warbler

A social network site like Twitter built with Python, Flask, and PostgreSQL.

[Video Demo](https://www.loom.com/share/915950e5ecb04c10987f4e517dfcfcf9?sid=1f38919b-1ecb-4cd2-aeeb-ce9a1d0b3cf0)
[Live Demo](https://cpa-warbler.onrender.com/)

## Run Locally

Create Python virtual environment:
```sh
cd flask-warbler/
python3 -m venv venv
source bin/venv/activate
pip install -r requirements.txt
```

Set up the database (PostgreSQL):
```sh
psql
CREATE DATABASE warbler;
```

Create an `.env` to hold configuration for database url and secret key.

Seed the database and start the server from virtual environment:
```sh
python seed.py
flask start
```

## Authors

- [Chris Alley](https://github.com/cp-alley)
- [Michael Griffin](https://github.com/michael-griffin)
