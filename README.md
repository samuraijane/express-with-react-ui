# Express With React UI

## Summary

**Express With React UI** is a starting point to build a full-stack Node/JavaScript application in which an express server renders a user interface generated by a **create-react-app** project. It is heavily influenced by [a similar project](https://github.com/mars/heroku-cra-node) created by Mars Hill.

## Installation

- Install the dependencies for express ---> `npm install`
- Rename **.env-example** to **.env** ---> `mv .env-example .env`
- Initiate a react project ---> `npx create-react-app react-ui --use-npm`
- Change your location to **react-ui** ---> `cd react-ui`
- Delete react's **.gitignore** ---> `rm .gitignore`
- Delete react's **README.md** ---> `rm README.md`

## Up and running

- Inside **react-ui/**, Create react's **build/** directory ---> `npm run build`
- Change your location to the root directory ---> `cd ..`
- Start the server in development mode ---> `npm run dev`
- In a browser, navigate to **localhost:8080**

## Building the react part of the application

Because the contents of **react-ui/build/** are static, any changes you make in the react part of the application will not be reflected at **localhost:8080** unless you run `npm run build` after each change. Since this slows develoment, run `npm run start` inside of **react-ui** and then navgiate to **localhost:3000** in a browser to see changes as you build in react.

## Heroku

This application can easily be deployed to Heroku. Details forthcoming.
