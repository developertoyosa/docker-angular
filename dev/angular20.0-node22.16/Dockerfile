#imagen base LTS
FROM node:22.16-alpine3.21

#carpeta predeterminada
WORKDIR /app

RUN apk update && apk add --no-cache \
    rsync \
    openssh-client \
    sshpass

#instalación del framework
RUN npm install -g @angular/cli@20.0.3

USER node

#inicio de la shell
CMD ["/bin/sh"]
