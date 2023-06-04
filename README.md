# Typescript MERN THRIFTRIP

1. Introduction
2. Install Tools
3. Create Typescript React App By Vite
4. Create Git Repository
   1. add README.md
   2. create github account
   3. connect vs code to github
   4. publish repository
5. List Products
   1. create Product type
   2. create products array
   3. add product images
   4. render products
6. Add React Bootstrap
   1. npm install react-bootstrap bootstrap
   2. import bootstrap css
   3. update App.tsx
7. Add page routing
   1. npm i react-router-dom
   2. create route for home page
   3. create router for product page
   4. add helmet for setting page title
8. Create NODE.JS Server
   1. create backend folder and run npm init
   2. npm install express
   3. npm install --save-dev typescript ts-node-dev @types/express
   4. @typescript-eslint/parser @typescript-eslint/eslint-plugin
   5. create src-index.ts
   6. create route for / return backend is ready.
   7. copy data.ts from frontend to backend
   8. create route for /api/products
   9. return products
   10. run npm start
9. Fetch Products From Backend
   1. npm install axios
   2. set axios base url
   3. use effect hook
   4. use reducer hook
10. Creating Rating ProductItem Components
11. Set Page Title
12. Load Products By React Query
13. Create Product Page
14. Create React Context
15. Connect To MongoDB
16. Implement Add To Cart
17. Add To Cart In Product Page
18. Create Cart Page
19. Implement Remove From Cart
20. Create User Signin Api
21. Create User Sign In Page
22. Register User
23. Create Shipping Page
24. Create Payment Page
25. Build Order Api
26. Create Place order Page
27. Create Order Page
28. Pay Order By PayPal
29. Create Order History Page
30. Make Website Like Amazon Dupe
31. Publish Website On A Render
32. Create Profile Page
33. Add-Sidebar-Searchbox

## everything you will see in this application

- Creating react application by Vite in TypeScript
- Defining and exporting Types like product, orders and user in frontend
- Creating e-commerce pages like cart, checkout and place order using React Router Dom
- Using React hooks to handle form inputs and fetch backend api
- Managing and monitoring application state by React Context
- Handling shopping cart using reducers and local storage
- Building backend web api by node.js, express.js and MongoDB
- Handling authentication and authorization using JsonWebToken and express middleware.
- Deploying your application on cloud servers like Render
- PayPal and Stipe for online payment,
- Render for deployment
- Google Map for locate customer address on map
- Mailgun to email order receipt to user

## how to run it locally

## create .env File

- duplicate .env.example in backend folder and rename it to .env

### 3. Setup MongoDB

- Local MongoDB
  - Install it from [here](https://www.mongodb.com/try/download/community)
  - In .env file update MONGODB_URI=mongodb://localhost/amazona
- OR Atlas Cloud MongoDB

  - Create database at [https://cloud.mongodb.com](https://cloud.mongodb.com)
  - In .env file update MONGODB_URI=mongodb+srv://your-db-connection

  ### 4. Run Backend

```
$ cd backend
$ npm install
$ npm start


### 5. Run Frontend

```

# open new terminal

$ cd frontend
$ npm install
$ npm start

```

```

### 6. Seed Users and Products

- Run this on browser: http://localhost:5000/api/seed
- It returns admin email and password and 6 sample products

### 7. Admin Login

- Run http://localhost:3000/signin
- Enter admin email and password and click signin

# .env file example

MONGODB_URI=mongodb://localhost/thriftrip
JWT_SECRET=somethingsecret
PAYPAL_CLIENT_ID=sb
PORT=4000
