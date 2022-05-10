# simple-express-rest-api

A simple REST api built with express simulating an api for managing subscriber data in a mongodb database.

### Running locally

Clone the repo:

```
git clone https://github.com/shan8851/simple-express-rest-api.git
```

install dependencies:

```
npm i
```

Create a `.env` file and add your mongodb database URL, example:

```
DATABASE_URL=mongodb://localhost/subscribers
```

Start the server

```
npm run dev
```

There are some sample requests in the `route.rest` file.
