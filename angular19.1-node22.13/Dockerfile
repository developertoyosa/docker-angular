#imagen base LTS
FROM node:22.13-alpine3.21

#carpeta predeterminada
WORKDIR /project

#actualiza dependencias
RUN apk update

#instalación del framework
RUN npm install -g @angular/cli@19.1.4

USER node

#inicio de la shell
CMD ["/bin/sh"]
