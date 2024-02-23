#imagen base
FROM node:16.19-alpine3.16

#carpeta predeterminada
WORKDIR /project

#actualiza dependencias
RUN apk update

#instalación del framework
RUN npm install -g @angular/cli@14.2.2

USER node

#inicio de la shell
CMD ["/bin/sh"]
