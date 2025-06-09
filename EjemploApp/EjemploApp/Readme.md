

```bash
cd /workspaces/docker_net/EjemploApp/EjemploApp
docker build -f Dockerfile -t ejemploapp:v0.1 .
docker images
docker run -d --name ejemploapp -p8080:8080 ejemploapp:v0.1
```


## listar los contenedores 
```bash
docker image ps
```

## parar el contenedor
```bash
docker stop ejempapp
```

## borrar el contenedor
```bash
docker rm ejemploapp
```

## borrar imagen
```bash
docker rmi ejemploapp:v0.1
```