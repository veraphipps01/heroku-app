version: '3.4'

services:
  herokudockerapp:
    image: herokudockerapp
    build:
      context: .
      dockerfile: ./Dockerfile
    environment:
      NODE_ENV: production
    ports:
      - 3000:3000
