FROM node:12.18.3-buster

WORKDIR /app/frontend

COPY package*.json ./

RUN npm install

COPY . . 

#develop mode
EXPOSE 3000

CMD ["npm", "run" ,"start"]

#Production mode:
#CMD ["npm", "run" ,"build"]
#and Copy the files made in build directory to the container