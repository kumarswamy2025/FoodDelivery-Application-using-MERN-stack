<h1 align="center">Food Delivery</h1>
  
  Tomato is a MERN (MongoDB, Express.js, React, Node.js) stack project that includes a sign-in/sign-up page with authentication, a frontend with dark and light themes, a backend with MongoDB database integration, and a payment system using Stripe. It also features an admin panel with dark and light themes.

 ## Technologies Used 
  <p align="center">
    <img alt="Language" src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB"/>
    <img alt="Language" src="https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E"/>
    <img alt="Language" src="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white"/>
    <img alt="Language" src="https://img.shields.io/badge/Express.js-404D59?style=for-the-badge"/>
    <img alt="Language" src="https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white"/>
    <img alt="Language" src="https://img.shields.io/badge/CSS-239120?&style=for-the-badge&logo=css3&logoColor=black"/>
    <img alt="Language" src="https://img.shields.io/badge/HTML-239120?style=for-the-badge&logo=html5&logoColor=black"/>
    <img alt="Language" src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"/>
    <img alt="Language" src="https://img.shields.io/badge/Stripe-626CD9?style=for-the-badge&logo=Stripe&logoColor=white"/>
  </p>
  
## DEMO 

![Picture](https://raw.githubusercontent.com/fr0st-iwnl/assets/main/thumbnails/tomato.png)


 Sign-in Page: Users can sign in to access additional features <br>

![image](https://github.com/Sumithra49/Tomato-Food-delivery/assets/141726527/bce3b2c2-c355-41ef-9ab9-64372d55c373)

 Menu Exploration:Users can explore the restaurant's menu items categorized by different food types.<br>
 ![image](https://github.com/Sumithra49/Tomato-Food-delivery/assets/141726527/bf7d10dc-fec3-4090-8329-8dc7b0488fee)

Adding to Cart: Users can add items to their cart from the menu.<br>
![image](https://github.com/Sumithra49/Tomato-Food-delivery/assets/141726527/fabe8daa-a88f-4b77-bcce-bd5ed4d6fc37)

Filtering: Users can filter menu items based on various criteria such as category, or dietary preferences.<br>
![image](https://github.com/Sumithra49/Tomato-Food-delivery/assets/141726527/d3373fe4-0b14-4f89-ade2-cbaec08796b7)

Cart Management: Users can view their cart, remove items, and proceed to checkout.<br>
![image](https://github.com/Sumithra49/Tomato-Food-delivery/assets/141726527/80fba764-bc79-4749-80cb-6dfa675ee8e1)

Order Placement: Users can input delivery information and place orders.<br>
![image](https://github.com/Sumithra49/Tomato-Food-delivery/assets/141726527/de526971-c9c7-4235-93b2-dc2690c25b5d)

Responsive Design: The application is responsive and suitable for various screen sizes.<br>
![image](https://github.com/Sumithra49/Tomato-Food-delivery/assets/141726527/675a6a1c-e7db-4464-82e4-9c6755ddc715)




## Features

- Sign-in/sign-up functionality with authentication.
- Frontend with dark and light themes.
- Backend with MongoDB database integration.
- Payment system using Stripe.
- Admin panel with dark and light themes.
- The main features are:

- Complete guidance on the UI for the ordering process.
- 2 different roles (Role Based Access Control):
  - `Manager`: Can process the orders received in Real time, view a history, add new restaurants and new meals. Can change the order status.
  - `User`: Can order from the restaurants. Also view a orders history.
- Use of `state-machine` to validate transitions of order status.
- Follow React and Node.js best practices.

## Installation

<h2>How to install/setup the Front-End</h2>

> Open a terminal in VS Code and go into the frontend folder and then run

>❗Open the frontend first [http://localhost:5173](http://localhost:5173)


```
npm install
npm run dev
```


<h2>How to install/setup the Admin Page</h2>

> Open a terminal in VS Code and go into the admin folder and then run

>❗Open the admin after the frontend. [http://localhost:5174](http://localhost:5174)

```
npm install
npm run dev
```
   
<h2>How to install/setup the Backend</h2>

> Open a terminal in VS Code and go into the backend folder and then run.

```
npm start server
```

- [ ] Remember to include your Database in db.js and your Stripe Secret Key in .env but donot push on github.


## MERNJS stack

- [React](https://reactjs.org) and [React Router](https://reacttraining.com/react-router/) for frontend.
- [Express](http://expressjs.com/) and [Node](https://nodejs.org/en/) for the backend.
- [MongoDB](https://www.mongodb.com/) for the database.
- [Redux](https://redux.js.org/basics/usagewithreact) for state management between React components.

