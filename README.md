# EcommEasy - Ecommerce Progressive Web Apps
EcommEasy allows you to create PWA ready E-commerce Application built with React and Node.js.

Built with:
* Node.js v8.9
* Express
* Babel
* WebPack 4
* MongoDB

## How to setup this repo?

### EcommEasy Backend (API) Installation
  
  - **Clone Git repository**
  ```shell
  git clone https://github.com/EcommEasy/EcommEasy
  cd EcommEasy
  ```
  - **Install dependencies**
  ```shell
  npm i
  ```
  
  - **Setup database** 
  
  Prepare database at this setup our database is empty. To add default data, indexes and access token we need to run:

  ```shell
  npm run setup <email> <domain>
  ```
  
  - We don't have real domain, so we'll use our local domain:
    ```shell
    npm run setup admin@example.com http://localhost:3000
    ```

  - This script will add token with email admin@example.com and my domain to http://localhost
    
  - **Start application in the background**
  ```shell
  pm2 start process.json
  ```

  - or you can start the app in your terminal:  
  
  ```shell
  npm start
  ```
  
  - At this setup, we have api running on port 3001 and available at **http://localhost:3001**
  
  - For example, here is the default store settings: **http://localhost:3001/api/v1/settings**  
  
  ```shell
info: API running at http://localhost:3001
info: MongoDB connected successfully
  ```

### Requirements
* Node.js >= 8
* MongoDB >= 3.2


## Application Structure


## Licence

This software is provided free of charge and without restriction under the MIT License
