# SparkAge - Chat Application

SparkAge is Chat application build with the power of MERN Stack.

## Installation Guide

### Requirements

- [Nodejs](https://nodejs.org/en/download)
- [Mongodb](https://www.mongodb.com/docs/manual/administration/install-community/)

Both should be installed and make sure mongodb is Running.

```shell
git clone https://github.com/Srishashank2003/Messenger-Application
cd Messenger-Application
```

Now Rename env files from .env.example to .env

```shell
cd public
mv .env.example .env
cd ..
cd server
mv .env.example .env
cd ..
```

Now Install the dependencies

```shell
cd server
yarn
cd ..
cd public
yarn
```

Now just start the development server.

For Frontend.

```shell
cd public
yarn start
```

For Backend.

Open another terminal in folder, Also make sure mongodb is running in background.

```shell
cd server
node index.js
```

Done! Now open localhost:3000 in your browser.
