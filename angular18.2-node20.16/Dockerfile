#imagen base
FROM node:20.16-alpine3.20

#carpeta predeterminada
WORKDIR /project

#actualiza dependencias
RUN apk update

#instalación del framework
RUN npm install -g @angular/cli@18.2.0

USER node

#inicio de la shell
CMD ["/bin/sh"]
