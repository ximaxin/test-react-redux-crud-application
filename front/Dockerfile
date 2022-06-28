FROM node:16.15.1
WORKDIR /front
RUN npm install yarn && yarn global add create-react-app # build時のcode
COPY . .
RUN yarn install --prod

# https://blog.shinonome.io/nodejs-docker/ 参照