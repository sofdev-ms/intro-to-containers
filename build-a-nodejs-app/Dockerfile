FROM node:12-stretch

# remove root-user
USER node 

WORKDIR /home/node/code

COPY --chown=node:node index.js index.js



CMD ["node" , "index.js"]