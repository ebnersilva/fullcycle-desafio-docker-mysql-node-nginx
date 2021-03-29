FROM node:15

# Digo qual vai ser o diretório de trabalho la dentro do container
WORKDIR /usr/src/app

# Copio tudo que está na pasta atual para o workdir do meu build
COPY . .

RUN apt-get update && apt-get install -y wget

ENV DOCKERIZE_VERSION v0.6.1
RUN wget https://github.com/jwilder/dockerize/releases/download/$DOCKERIZE_VERSION/dockerize-linux-amd64-$DOCKERIZE_VERSION.tar.gz \
    && tar -C /usr/local/bin -xzvf dockerize-linux-amd64-$DOCKERIZE_VERSION.tar.gz \
    && rm dockerize-linux-amd64-$DOCKERIZE_VERSION.tar.gz

# Libero a porta 3000 para que outros containers consigam enxergar essa porta
EXPOSE 3000

# Rodamos esse comando para subir a aplicação
# CMD ["node", "index.js"]