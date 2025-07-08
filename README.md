# Flask App

A simple flask app that hosts on port 5000.

## build commands 

```bash
python3 -m venv venv
source ./venv/bin/activate
pip install -r requirements.txt
```


## start commands

```bash
source ./venv/bin/activate
python app.py
```

# Docker App

Same server using docker with different port for testing properly. Port: 

## build commands 

```bash
sudo docker build -t docker-flask-app .
```


## start commands

```bash
sudo docker run -p 8080:5000 docker-flask-app
```

