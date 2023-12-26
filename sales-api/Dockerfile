FROM node:18
WORKDIR .
COPY package*.json ./
RUN yarn 
COPY . .
EXPOSE 8082
CMD [ "node","app.js"]

#docker image build -t sales-api .

#docker run --name sales-api -p 8082:8082 sales-api

#docker run --name sales-api -e PORT=8082 -p 8082:8082  sales-api