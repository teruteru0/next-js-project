FROM node:15.8.0-alpine3.10

ENV PORT 3000

WORKDIR /my_app
COPY ./my_app .

EXPOSE ${PORT}

CMD ["yarn", "dev"]