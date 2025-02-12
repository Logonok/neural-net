# Neural Network App
 
Train, test and operate neural networks to recognize handwritten digits. 

[![Neural Network Demo](doc/screen-01.png)](http://nervebit.com/neural-net)

## Docker installation

Clone application to /app
```sh
cd /app
docker-compose up -d mongo
docker-compose up --build installer
docker-compose up -d server
```

## Typical installation

#### Install environment
- [Node.js](https://nodejs.org) (version 14)
- [MongoDB](https://www.mongodb.com/download-center/community) (version 4)

#### Linux
Clone application to /app
```sh
cd /app
npm install
NODE_ENV=development node console/install
NODE_ENV=development node console/start
```

#### Windows
Clone application to c:/app
```sh
cd c:/app
npm install
set NODE_ENV=development
node console/install
node console/start
```

## Usage

Web interface: [http://localhost:3000](http://localhost:3000)

Sign in as administrator:
```sh
Email: a@a.a
Password: 123456
```