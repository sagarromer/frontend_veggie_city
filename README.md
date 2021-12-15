# online vegitable market
<p>
  <img src="https://img.shields.io/badge/React-16.10.+-lightblue.svg">
  <img src="https://img.shields.io/badge/Redux-4.0.+-purple.svg">
  <img src="https://img.shields.io/badge/Nodejs-10.16.+-green.svg">
  <img src="https://img.shields.io/badge/Ex<press-4.17.+-black.svg">
</p>
VeggieCity is open source ecommerce application for vegitable buying.
Application consists of following parts:

1. Store front - React based SPA with server side rendering
2. [API Backend](https://github.com/sagarromer/backend_veggie_city) - Node.js, Express, MongoDb

## Screenshots

### Store home
![frontend-veggie-city](/public/site/home.PNG)


### Admin orders
![frontend-veggie-city](/public/site/admin_orders.PNG)

### Admin products
![frontend-veggie-city](/public/site/admin_products.PNG)

### Food Details
![frontend-veggie-city](/public/site/food_details.PNG)

### create new account
![frontend-veggie-city](/public/site/create_new_account.PNG)

### order details
![frontend-veggie-city](/public/site/order_details.PNG)

### order history
![frontend-veggie-city](/public/site/order_history.PNG)

### payment method
![frontend-veggie-city](/public/site/payment_method.PNG)

### paypal payments
![frontend-veggie-city](/public/site/paypal_payments.PNG)

### place order
![frontend-veggie-city](/public/site/place_order.PNG)

### shipping details
![frontend-veggie-city](/public/site/shipping_details.PNG)

### shopping cart
![frontend-veggie-city](/public/site/shopping_cart.PNG)

### signin
![frontend-veggie-city](/public/site/signin.PNG)


## Live demo

* To view storefront, [click here](https://google.com)
* To view Backoffice, [click here](https://google.com)

## Features

customer:
1. select products and add to cart
2. change cart details such as product quantity and delete from cart
3. checkout
4. payments
5. update user profile
6. register as a new user and login
7. view my orders
8. search products 

Admin:

1. Login
2. Responsive design
3. Orders lists based on status
4. Change order status
5. View orders
6. Products list
7. View product 
8. Add / edit product 

## Dependencies

1. [React](https://reactjs.org/docs/getting-started.html) - ui
2. [Redux](https://redux.js.org/api/api-reference) - state managment
3. [Redux-thunk](https://github.com/reduxjs/redux-thunk) - side effects
4. [Formidable](https://github.com/node-formidable/node-formidable) - file uploads
5. [Jsonwebtoken](https://github.com/auth0/node-jsonwebtoken) - implementation of json web tokens
6. [Ant.Design](https://github.com/ant-design/ant-design) - react ui library
7. [Formik](https://github.com/jaredpalmer/formik) - forms for react
8. [Yup](https://github.com/jquense/yup) - form validation
9. [Axios](https://github.com/axios/axios) - http client
10. [React Router v4](https://reacttraining.com/react-router/web/guides/quick-start) - router
11. [Express](https://expressjs.com/) - web framework

## Setup
### Prerequisites
* Install Node.js >= 10
* Install MongoDB
### Seed database
* Go to 'backend'
* Install 'dependencies'
```
npm install
```
* Seed database
```
npm run seed
```
### Start backend
* Go to 'backends/express'
* Install dependencies
```
yarn install
```
* Start backend
```
yarn run start
```
### Start storefront
* Go to 'frontend'
* Install dependencies
```
npm install
```
* Buld storefront
```
npm run build:dev
```
* Start storefront
```
npm run start
```

## License

The MIT License (MIT)

Copyright (c) 2020-2021 sagara dissanayake

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

Coded with ❤️ by sagara dissanayake
