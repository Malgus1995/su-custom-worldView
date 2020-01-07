FROM node:8.10.0 


RUN mkdir /usr/src/app
WORKDIR /usr/src/app
ENV PATH /usr/src/app/node_modules/.bin:$PATH
RUN npm install --silent
RUN npm install react-scripts@2.1.3 -g --silent

COPY . /usr/src/app
CMD ["npm", "start"]