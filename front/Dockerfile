FROM node:16.15.1
WORKDIR /front
RUN npm install yarn && yarn global add create-react-app
RUN yarn add redux react-redux
COPY . .
RUN yarn install --prod

# https://blog.shinonome.io/nodejs-docker/ 参照