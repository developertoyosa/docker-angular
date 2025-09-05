#imagen base
FROM node:12.10.0-alpine

#carpeta predeterminada
WORKDIR /app

RUN apk update && apk add --no-cache \
    rsync \
    openssh-client \
    sshpass

#instalación del framework
RUN npm install -g @angular/cli@11.2.6

USER node

#inicio de la shell
CMD ["/bin/sh"]
