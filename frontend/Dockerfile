# Usa un'immagine base di Node.js
FROM node:latest

# Imposta la directory di lavoro nel contenitore
WORKDIR /app

# Copia i file dell'app React nel contenitore
COPY . /app

# Installa le dipendenze
RUN npm install
RUN apt-get update && \
    apt-get -y install git

# Avvia l'app React
CMD ["npm", "start"]

