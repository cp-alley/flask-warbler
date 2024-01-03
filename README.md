# Warbler

A social network site like Twitter built with Python, Flask, and PostgreSQL.

[Live Demo](https://warbler-r33-loc2.onrender.com/)

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
