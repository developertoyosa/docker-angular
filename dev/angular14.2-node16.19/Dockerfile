#imagen base
FROM node:16.19-alpine3.16

#carpeta predeterminada
WORKDIR /app

RUN apk update && apk add --no-cache \
    rsync \
    openssh-client \
    sshpass

#instalación del framework
RUN npm install -g @angular/cli@14.2.2

USER node

#inicio de la shell
CMD ["/bin/sh"]
