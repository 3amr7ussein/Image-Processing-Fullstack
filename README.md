## Image Processing Fullstack Application (Mobile-Responsive)

####

**This is my first full stack application** , An image processing application build to apply some processes on image server-side, built with HTML, CSS, React, Node, Express & TypeScript . 

it is a one week project was created to be submitted as 1st task in my Udacity FWD Web-Development Schoolarship .

<details open ><summary> 
  
  ### Screen Shots
  </summary>
  
  Desktop | Mobile
-|-
<img src="https://github.com/3amr7ussein/Image-Processing-Fullstack/blob/main/server/assets/full/Image-Resizing-Desktop.jpg" width='700'/> | <img src="https://user-images.githubusercontent.com/34787413/207199430-3a157ae0-e7c3-46eb-a4ab-dbd49f762faa.jpg" width="200" />
</details  >

  <details ><summary>  
  
### How To Run Project
   </summary>  
  
####  Run Server (Backend)
1- Clone project into your local machine (npm & git must be globally installed).
  
2- use your terminal to `cd server` and then `npm run install` ,this will install the required packges to run this project.

3- run `npm start` or `npm run start:prod` , to run project in development or production on PORT:5000 .

###### Other Scripts
  Script | Functionality
  :-|:-
  `npm run test`  |  to build the project and start unit testing with jasmine
  `npm run format` |  to format code.
 `npm run lint`   |  to Find problems in code

####  Lets Run Client-Side (Frontend)
  Hint : Keep the server running and open new terminal

  1- `cd client` and then `npm run install` ,to install the required packges to run client code.

  2- run `npm start` , and visit to http://localhost:3000

 </details>

  <details><summary> 
  
### API Endpoints

  </summary>
    
  
| HTTP Verbs | Endpoints             | Action                                                                         |
| ---------- | --------------------- | ------------------------------------------------------------------------------ |
| GET        | /api/images/all       | To retrive list of file in Full directory as an Array                          |
| GET        | /api/images/:filename | To retrive single image by file name                                           |
| GET        | /api/images?          | To retrive a resized image by passing query parameters (filename,width,height) |
| POST       | /api/upload           | To upload jpg image to /full directory                                         |
  
  
</details>


  
  <details><summary> 
  
###  Technologies Used
</summary>

  - [NodeJS](https://nodejs.org/) This is a cross-platform runtime environment built on Chrome's V8 JavaScript engine used in running JavaScript codes on the server. It allows for installation and managing of dependencies and communication with databases.

  - [ExpressJS](https://www.expresjs.org/) This is a NodeJS web application framework.

  - [ReactJs](https://reactjs.org/) A JavaScript library for building user interfaces

  - [axios](https://axios-http.com/docs/intro/) Axios is a promise-based HTTP Client for node.js and the browser. It is isomorphic (= it can run in the browser and nodejs with the same codebase).
    
  </details>
