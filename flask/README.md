# Flask

Dokumentacja: [http://flask.pocoo.org/docs/1.0/](http://flask.pocoo.org/docs/1.0/)

Instalujemy zależności:
```
sudo apt-get update
sudo apt-get install python3-venv
```

Jak przygotować środowisko:
```
python3 -m venv venv
source venv/bin/activate
pip install flask
```

Jak uruchomić aplikację:
```
export FLASK_RUN_PORT=8080
export FLASK_RUN_HOST=0.0.0.0
export FLASK_APP=flaskr
flask run
```

Aby zatrzymać aplikację - Ctrl + C

