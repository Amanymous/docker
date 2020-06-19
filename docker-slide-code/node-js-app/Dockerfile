FROM alpine
LABEL maintainer="aman.mirza9@yahoo.com"
RUN apk add --update nodejs nodejs-npm
COPY . /src
WORKDIR /src
RUN npm install
ENV CREATEDBY="Aman Mirza"
EXPOSE 8080
ENTRYPOINT ["node", "./app.js"]
