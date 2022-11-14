## How to run

```
docker build -t exp:v1 -f docker/Dockerfile .
docker run -it exp:v1
```

```
export FLASK_APP=api/app.py ; flask run
```