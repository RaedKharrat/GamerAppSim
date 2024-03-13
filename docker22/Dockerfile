FROM undefined:undefined-alpine

    # Ajoutez d'autres instructions Docker en fonction de votre configuration

    WORKDIR /opt/app

    COPY package*.json ./

    RUN npm install

    COPY . .

    ENV APP_KEYS=98798
    ENV NODE_ENV=ygggguy

    EXPOSE undefined

    CMD ["npm", "start"]
    