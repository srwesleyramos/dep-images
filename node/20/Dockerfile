# Usando a imagem do Node na versão 20
FROM node:20

# Usando o diretório virtual do app
RUN         useradd -s /bin/bash depcloud
USER        depcloud
WORKDIR     /home/depcloud

# Comando para executar a aplicação
CMD npm install --omit=dev && npm start