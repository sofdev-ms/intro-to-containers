FROM node:12-stretch

RUN npm i -g nodemon

USER node

RUN mkdir /home/node/code

WORKDIR /home/node/code

COPY --chown=node:node . .

RUN npm ci 

#EXPOSE 3000 , use it with -P flag and then check which port has actually been exposed

CMD ["nodemon" , "index.js"]