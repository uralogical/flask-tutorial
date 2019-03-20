# flask-tutorial

[flask-tutorial-handson](https://github.com/uralogical/flask-tutorial-handson) の完成版です。

## venv setup

```
$ python3 -m venv venv
$ . venv/bin/activate
(venv) $
```

## flask setup

```
(venv) $ pip install Flask
(venv) $ flask --version
Flask 1.0.2
Python 3.7.2 (v3.7.2:9a3ffc0492, Dec 24 2018, 02:44:43) 
[Clang 6.0 (clang-600.0.57)]
```

## run flask app (Mac)

``` 
(venv) export FLASK_APP=flaskr
(venv) export FLASK_ENV=development
(venv) flask run
```

## run flask app (Windows)

```
(venv) set FLASK_APP=flaskr
(venv) set FLASK_ENV=development
(venv) flask run
```
