FROM node:10

RUN mkdir /project
WORKDIR /project

COPY . .

RUN npm install -g @angular/cli
RUN yarn install
CMD ["ng", "serve", "--disableHostCheck", "true", "--host", "0.0.0.0"]
