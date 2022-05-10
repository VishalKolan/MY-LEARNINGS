# Specify a base image
FROM node:14-alpine

WORKDIR /usr/app
COPY ./package.json ./
#install some dependencies
RUN npm install
COPY ./ ./

#Default connamd
CMD ["npm", "start"]

#ENTRYPOINT ["",""]
