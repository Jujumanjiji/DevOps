FROM node:8.9.3

WORKDIR /home/farsen/wik-devops-3tp

# Installations des dépendences de l'application

COPY package*.json ./


RUN npm install 
# Pour bundle le code source de l'application

COPY . .

EXPOSE 8080
CMD [ "npm", "start" ]

