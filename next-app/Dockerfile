FROM node:20.11.1

WORKDIR /app

COPY . /app

RUN apt-get update && apt-get install -y vim
RUN yarn install
RUN chmod -R o+w .

CMD ["yarn", "dev"]