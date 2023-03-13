# python-rest-fastapi

## creating and activating venv
To create venv issue following command:
```bash
python3 -m venv venv_name
```
where **venv_name** is your name of virtual environment.

To activate venv issue following command:
```bash
source venv_name/bin/activate
```

To deactivate venv issue:
```bash
deactivate
```

## installing dependences
To install required dependences issue following command:
```bash
pip3 install -r requirements.txt
```

## running the application
To start the application issue following command:
```bash
uvicorn app.main:app --host 0.0.0.0 --port 8080
```
Now you can open your browser and navigate to http://0.0.0.0:8080

## Building and running docker
```bash
docker build -t fastapiapp .
```

```bash
docker run -p 8080:8080 fastapiapp
```
