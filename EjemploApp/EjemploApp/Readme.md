

```bash
cd /workspaces/docker_net/EjemploApp/EjemploApp
docker build -f Dockerfile -t ejemploapp:v0.1 .
docker images
docker run -d --name ejemploapp -p8080:8080 ejemploapp:v0.1
```

```
docker stop ejempapp
docker rm ejemploapp
docker rmi ejemploapp:v0.1
```