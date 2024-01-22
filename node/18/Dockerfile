# Usando a imagem do Node na versão 18
FROM node:18

# Usando o diretório virtual do app
RUN         useradd -s /bin/bash depcloud
USER        depcloud
WORKDIR     /home/depcloud

# Comando para executar a aplicação
CMD npm install --omit=dev && npm start