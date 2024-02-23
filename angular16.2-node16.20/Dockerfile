#imagen base
FROM node:16.20.2-alpine3.18

#carpeta predeterminada
WORKDIR /project

#actualiza dependencias
RUN apk update

#instalación del framework
RUN npm install -g @angular/cli@16.2.0

USER node

#inicio de la shell
CMD ["/bin/sh"]
