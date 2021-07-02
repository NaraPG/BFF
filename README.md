# Backend For Frontend

## This repository
> In this course we integrate frontend and backend constructed previously in the JavaScript academy to display PlatziVideo in different alternatives enviroments.

## Introduction
#### The BFF 
> - Call the relevant microservices APIs and obtain the needed data.
> - Format the data based on the frontend representation.
> - Send the formatted data to the frontend.
> A BFF helps to streamline data representation and takes up the responsibility of providing a well-focused interface for the frontend.
Another great way to simplify your backend-frontend relation is by sharing types between them.

## BFF implementation
> Building a BFF allows you to intelligently make batch calls to other backends/ microservices and return the data all at once, or return a more convenient representation by transforming and formatting the data.
> The BFF pattern not only helps development, but it also helps improve user experience drastically. Therefore, it is essential to consider data optimizations and aggregations while keeping the BFF focused on its frontend.

<img src="https://user-images.githubusercontent.com/79294934/124283705-d2a6b600-db11-11eb-8ec6-3b0cdbeb9971.png"></img>


## Commands
> To habilitate develop in a local way
> ```
> npm run start:dev
> ```
> Run tests
> ```
> npm run test
> ```
> To run one test
> ```
> jest src/frontend/__test__/actions/index.test.js
> ```
> To generate a report of the tests
> ```
> npm run test:coverage
> ```


## Dependencies
> - Install [VS Code](https://code.visualstudio.com/download)
> - Install [Node.js](https://nodejs.org/en/)
> - Install nodemon (Optional)
>   * Cloning with git or by using npm (the recommended way):
> ```
> npm install -g nodemon
> ```
>   * You can also install nodemon as a development dependency:
>   ```
>   npm install --save-dev nodemon
>   ```

## Run Code
> - Use `npm i` to install the project dependencies
> - For Windows use the command `cd [path]` and `npx nodemon [script]` to run the project automatically

## Technologies
> - JavaScript
> - SCSS

_Created by Nara Peña Gámez._
