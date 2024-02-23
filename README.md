## Instalar docker

- [Linux](https://docs.docker.com/install/)

- [Windows](https://docs.docker.com/docker-for-windows/install/)

- [Mac](https://docs.docker.com/docker-for-mac/install/)


> ## Build docker

Esto crea la imagen del docker para verificar que todo este en buen funcionamiento

`docker build -t angular-dev:xx.y-nodexx.yy .`

> #### Crear un docker de prueba

`docker run -it --name docker-build-test -v $(pwd):/project developertoyosa/angular-dev:xx.y-nodexx.yy`

> #### Publicar docker 

`docker build -t developertoyosa/angular-dev:xx.y-nodexx.yy .`

`docker login`

`docker push developertoyosa/angular-dev:xx.y-nodexx.yy`

> ## Verificación de versiones
`node -v`

`npm -v`

`ng version`

