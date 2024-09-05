# SafePulse Project MERN stack:
SafePulse is a MERN stack web application designed to provide real-time emergency assistance. 

Utilizing Socket.io and advanced geolocation features, the platform enables civilians to instantly alert nearby law enforcement by sharing their live location with a single click. 

This seamless communication system aims to enhance public safety and response times during critical situations.

## Tech Stack

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black) ![Node.JS](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white) ![Express.JS](https://img.shields.io/badge/Express.js-404D59?style=for-the-badge) ![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white) 

## How to install:
- Install [NodeJS](https://nodejs.org/en/) and [MongoDB](https://docs.mongodb.com/)
- Fork this project and clone it in your machine
- `cd` to your project root and run `npm install`
- run `mongoimport --db SafePulse --collection cops --drop --file ./db/cops.json` to import sample cop information in MongoDB
- run `mongoimport --db SafePulse --collection requests --drop --file ./db/crime-data.json` to import sample crime information in MongoDB

## How to run:
- Run `node app.js` in your project root folder
- Open a demo civilian page by going to http://localhost:8000/civilian.html?userId=YOURNAME
- Open 3 or more cop pages from the imported cop profiles on separate tabs - [01](http://localhost:8000/cop.html?userId=01), [02](http://localhost:8000/cop.html?userId=02), [03](http://localhost:8000/cop.html?userId=03), [04](http://localhost:8000/cop.html?userId=04), [05](http://localhost:8000/cop.html?userId=05), [06](http://localhost:8000/cop.html?userId=06), [07](http://localhost:8000/cop.html?userId=07)


