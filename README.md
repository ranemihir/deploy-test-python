# Flask App

A simple flask app that hosts on port 5000.

## build commands 

```bash
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```


## start commands

```bash
python app.py
```

# Docker App

Same server using docker with different port for testing properly. Port: 

## build commands 

```bash
docker build -t docker-flask-app .
```


## start commands

```bash
docker run -p 8080:5000 docker-flask-app
```

