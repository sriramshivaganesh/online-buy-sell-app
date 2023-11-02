# online-buy-sell-app

This Repository contains the code for online buy and sell app, with react as the frontend, flask as backend and mongodb as the database. the backend is also docker containerized.

To start the project run the app.py and upload data of your choice using postman 

example json data is in the form of 


    {
      "productId": "car101",
      "category": "car",
      "name": "Maruti Suzuki Swift",
      "description": "2 years old, Excellent condition",
      "price": "450000",
      "image": "https://apollo-singapore.akamaized.net/v1/files/bi3u9hzs958w2-IN/image;s=780x0;q=60"
    }

catogery must be only car/ bike/ mobile

to run react 
use commands 
npm install
npm start