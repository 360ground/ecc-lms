# This repo contains both the angular app and express app that runs in collabaration with canvaslms system

## How to run angular app
 1. cd into frontend folder
 2. install dependencies $ npm i
 3. run dev server $ npm run start

## To build angular app
 1. cd into frontend folder
 2. run $ npm run build
 
 
 ## how to run express api
  1. cd into backend folder
  2. install dependencies $ npm i
  3. run start script $ npm run start
  
 #### NB. when running the express api make sure that the redis server and the mysql server configuration match your enviroment. ie if your servers are hosted in different location than stated in the env file change them. duhh
 #### Also the express api relies heavily on the canvas api so make sure to update your env file to point to the required canvas api and dont forget to generate the required access token to interoperate with the canvas api other wise the app wont work. for more info - https://community.canvaslms.com/t5/Admin-Guide/How-do-I-obtain-an-API-access-token-in-the-Canvas-Data-Portal/ta-p/157 
