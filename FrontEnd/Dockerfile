# pull official base image
FROM node:13.12.0-alpine

RUN mkdir -p /FrontEnd

# set working directory
WORKDIR /FrontEnd 
 
# add `/app/node_modules/.bin` to $PATH
ENV PATH /FrontEnd/node_modules/.bin:$PATH

# install app dependencies
COPY package.json ./
COPY package-lock.json ./
RUN npm install

# add app
COPY . ./

# start app
CMD ["npm", "start"]    
