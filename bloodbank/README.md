<div align="center">
  <img src="https://image.flaticon.com/icons/png/128/2069/2069743.png">
  <h1>Blood Bank</h1>
</div>



## 📝 Table of Contents

- [About](#-about-)
- [Getting Started](#-getting-started-)
- [Testing](#-running-the-tests-)
- [Deployment](#-deployment-)
- [Built Using](#-built-using-)
- [Authors](#-authors-)
- [Acknowledgments](#-acknowledgements-)

## 🧐 About

Blood Bank is a very simple yet functional and secure Blood Bank Web Application.

If you are familiar enough in a beginner level with `Node JS` and `mongoose` this is a good project to clone and try to replicate.

## 🏁 Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See [deployment](#deployment) for notes on how to deploy the project on a live system.

### Prerequisites

- Node > 8
- Git
- MongoDB > 3.0


```bash
npm install
```

### Running Locally

Create a new file in root directory `.env`
Copy contents from `.env.expmple`
Make changes if required.

```bash
npm start
```

### Populating database with sample data

Edit JSON files under `util` for dummy data

```bash
npm run populate
```

## 🔧 Running the tests

Still in todos

## 🚀 Deployment

Make changes in `.env`

1. Set `DBURI` to your remote mongoDB URI
2. Scale the PORT accounrding to your host/server
3. Change NODE_ENV to production for `Morgan`
4. Remove everything after `DEBUG=`

## ⛏️ Built Using

- [MongoDB](https://www.mongodb.com/) - Database
- [Mongoose](https://mongoosejs.com/) - MongoDB Wrapper
- [Express](https://expressjs.com/) - Server Framework
- [NodeJs](https://nodejs.org/en/) - Server Environment
- [VS Code](https://code.visualstudio.com/) - Awesome IDE

## ✍️ Authors

[@mrsadik72](https://github.com/MrSadik72) - Initial work



## 🎉 Acknowledgements

- Hat tip to anyone whose code was used
- StackOverflow <3
