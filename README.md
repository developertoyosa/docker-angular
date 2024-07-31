## Versión de nodejs

https://nodejs.org/en/about/previous-releases

## Versión de angular de acuerdo al número
https://v16.angular.io/guide/versions

https://v17.angular.io/guide/versions

https://angular.dev/reference/versions


## Referencia específica de node en el package 
https://www.npmjs.com/package/@angular/cli/v/16.2.14?activeTab=code


## Instalar docker

- [Linux](https://docs.docker.com/install/)

- [Windows](https://docs.docker.com/docker-for-windows/install/)

- [Mac](https://docs.docker.com/docker-for-mac/install/)


> ## Build docker

Esto crea la imagen del docker para verificar que todo este en buen funcionamiento

## Convención de versión
De acuerdo al estandar https://semver.org/lang/es/ se debe contemplar dos número para xx (10) y para y (5) en el caso de angular 

Ejemplo:
10.5

En el caso de Nodejs xx (16) y para y(10)

Ejemplo:
16.10

Esto debido a que en angular y node tienes diferentes convenciones a seguir


`docker buildx build -t angular-dev:xx.y-nodexx.yy .`

> #### Crear un docker de prueba

`docker run -it --name docker-build-test -v $(pwd):/project developertoyosa/angular-dev:xx.y-nodexx.yy`

> #### Publicar docker 

`docker buildx build -t developertoyosa/angular-dev:xx.y-nodexx.yy .`

`docker login`

`docker push developertoyosa/angular-dev:xx.y-nodexx.yy`

> ## Verificación de versiones
`node -v`

`npm -v`

`ng version`

