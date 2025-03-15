# Streamlit deploy guide for Docker

**Build streamlit docker image**
```
docker build . -t python:streamlit
```

<br>

**Create the container volume before running docker compose**
```
docker volume create streamlit-data
```

<br>

**Deploy streamlit docker container**
```
docker compose up -d
```
