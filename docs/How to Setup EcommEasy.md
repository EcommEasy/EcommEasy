# Installation Guides
## Prerequisites

  - **Nginx `>= 1.14.0`**
  ```shell
  apt update && apt install nginx-full
  ```

  - **Mongodb `>= 3.2`**

  - **Node.js `v11.x`**
  
  NodeJS 11.x installation:
  ```shell
* Using Ubuntu
curl -sL https://deb.nodesource.com/setup_11.x | sudo -E bash -
sudo apt-get install -y nodejs
* Using Debian, as root
curl -sL https://deb.nodesource.com/setup_11.x | bash -
apt-get install -y nodejs
  ```
  - **NPM `>= 6.3.0`** 
  ```shell
  npm i -g npm
  ```

  - **PM2 `>= 3.0.3`**
  ```shell
  npm i -g pm2
  ```
  
## Setup Database
### Local Mongo Setup
follow mongo [instructions](https://docs.mongodb.com/manual/installation/) to install locally.
run `mongod`
### MongoDB Atlas Setup
