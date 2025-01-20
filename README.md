# Minimal Backend Api Deployment with PostgreSQL

To get set up, run:

```console
$ pipenv install && pipenv shell
$ python seed.py 
$ gunicorn app:app
```

## Routes 
```
http://127.0.0.1:8000/birds 
http://127.0.0.1:8000/birds/1
```