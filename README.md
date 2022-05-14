# Develop REST API with Flask and JWT authentication

# Installation

1. Clone this repo

```
git clone https://github.com/khangaitan/flask-rest-api-jwt-auth.git
```

2. Run 

```
cd flask-rest-api-jwt-auth
$ flask run
```

3. Create and SQLITE db

```
$ python3
>>> from api import db
>>> db.create_all()
>>> exit()
```

3. Check db exists

```
$ sqlite3
sqlite> .open api.db
sqlite> .tables
sqlite> .quit
```
