# nodeAuthApi
#### simple nodejs app to handle authentication in back-end 

# Getting Started
#### These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. 
## Installation
* Git clone this repo [here](docs).
* Run ```npm install``` to install node dependencies.
* Start MongoDB instance: ```mongod```
  * Set the enviroment variable **MONGO_URL**:
  * If you are using **mlab** as a database then example: ```**MONGO_URL**: malb mongodb://<username>:<password>@ds037997.mlab.com:37997/nodeapi ```
  * If you are using local mongo database then provide local database url e.g. ```mongodb://mongodb0.example.com:27017/admin```
  * For more detail on setup mongodb see [here](https://docs.mongodb.com/manual/reference/connection-string/)
* Set these enviroment variable to work with authentication:
  * ```
        JWT_SECRET=KHKDKOSHD*****23789HDC
        CLIENT_URL=http://localhost:5000/api to use reset-password work
    ```
* Run ```npm run dev ``` to start the nodemon daemon

# Running the tests
  * One can Use Postman to test the API's
