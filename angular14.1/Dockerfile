#imagen base
FROM node:14.20-alpine

#carpeta predeterminada
WORKDIR /project

#actualiza dependencias
RUN apk update

#instalación del framework
RUN npm install -g @angular/cli@14.1.3

USER node

#inicio de la shell
CMD ["/bin/sh"]
