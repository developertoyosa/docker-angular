#imagen base
FROM node:12.10.0-alpine

#carpeta predeterminada
WORKDIR /project

#actualiza dependencias
RUN apk update

#instalación del framework
RUN npm install -g @angular/cli@10.2.4

USER node

#inicio de la shell
CMD ["/bin/sh"]
