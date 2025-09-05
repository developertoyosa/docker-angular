#imagen base
FROM node:16.20.2-alpine3.18

#carpeta predeterminada
WORKDIR /app

RUN apk update && apk add --no-cache \
    rsync \
    openssh-client \
    sshpass

#instalación del framework
RUN npm install -g @angular/cli@16.2.0

USER node

#inicio de la shell
CMD ["/bin/sh"]
