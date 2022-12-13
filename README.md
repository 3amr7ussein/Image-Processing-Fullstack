# Image Processing Fullstack Application (Mobile-Responsive)

####

An image processing application build to apply some processes on image server-side, built with Node, Express, React, TypeScript and CSS. 



## How to run Server-Side (Backend)

1- Download and unzip the project directory.

2- use your terminal to `cd server` and then `npm run install` ,this will install the required packges to run this project.

3- run `npm start` or `npm run start:prod` , to run project in development or production on PORT:5000 .

run `npm run test` , to build the project and start unit testing with jasmine

run `npm run format` , to format code.

run `npm run lint` , to Find problems in code

### API Endpoints

| HTTP Verbs | Endpoints             | Action                                                                         |
| ---------- | --------------------- | ------------------------------------------------------------------------------ |
| GET        | /api/images/all       | To retrive list of file in Full directory as an Array                          |
| GET        | /api/images/:filename | To retrive single image by file name                                           |
| GET        | /api/images?          | To retrive a resized image by passing query parameters (filename,width,height) |
| POST       | /api/upload           | To upload jpg image to /full directory                                          |

## Now Lets Run Client-Side (Frontend)

### Keep the server running and open new terminal

1- `cd client` and then `npm run install` ,to install the required packges to run client code.
2- run `npm start` , and visit to http://localhost:3000

### Technologies Used

- [NodeJS](https://nodejs.org/) This is a cross-platform runtime environment built on Chrome's V8 JavaScript engine used in running JavaScript codes on the server. It allows for installation and managing of dependencies and communication with databases.
- [ExpressJS](https://www.expresjs.org/) This is a NodeJS web application framework.
- [ReactJs](https://reactjs.org/) A JavaScript library for building user interfaces
- [axios](https://axios-http.com/docs/intro/) Axios is a promise-based HTTP Client for node.js and the browser. It is isomorphic (= it can run in the browser and nodejs with the same codebase).
