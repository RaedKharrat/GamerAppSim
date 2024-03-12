FROM undefined:undefined-alpine

    # Ajoutez d'autres instructions Docker en fonction de votre configuration

    WORKDIR /opt/app

    COPY package*.json ./

    RUN yarn install

    COPY . .

    ENV APP_KEYS=undefined
    ENV NODE_ENV=undefined

    EXPOSE undefined

    CMD ["yarn", "start"]
    