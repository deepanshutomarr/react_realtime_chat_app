# Chat Application
 
A Realtime Chat Application build with the power of MERN Stack. 

## Live Link: 

https://realtimechatapplication-six.vercel.app/


## Installation Guide

### Requirements
- [Nodejs](https://nodejs.org/en/download)
- [Mongodb](https://www.mongodb.com/docs/manual/administration/install-community/)

### Installation

#### First Method
```shell
git clone https://github.com/deepanshutomarr/react_realtime_chat_app.git 
cd react_realtime_chat_app
```
Now rename env files from .env.example to .env
```shell
cd public
mv .env.example .env
cd ..
cd server
mv .env.example .env
cd ..
```

Now install the dependencies
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
yarn start
```
Done! Now open localhost:3000 in your browser.
