# nodetest1

This is a test run for creating a RESTful API using Node.js, Express.js and MongoDB. In order to use this project, follow the steps below. This project assumes you already have Node.js installed. You may notice that some of the dependencies are not up to date, and this is intentional in order to utilize the [tutorial](http://cwbuecheler.com/web/tutorials/2014/restful-web-app-node-express-mongodb/) made by [Christopher Buecheler](http://cwbuecheler.com/), which is highly recommended for further explanation of this project.

1. In terminal window, `mkdir <YOUR PROJECT NAME>`, then `cd <YOUR PROJECT NAME>`
2. Inside project folder, `git clone git@github.com:bam1056/nodetest1.git` then `cd nodetest1`
3. Download dependencies using `npm install`
4. Before continuing, you may need to install and configure Mongo for this project. Please follow the steps outlined below:
      * In terminal `brew install mongodb` 
      * Still inside your project folder, `mkdir data` then `cd data`
      * First, `mongod --dbpath c:\node\nodetest1\data\`. When says listening on port 27017, ready to go!
      * In new terminal window, `mongo`
      * Inside the mongo console window, `use nodetest1`
5. At this point, you should have a project ready to go to start listening for requests once you navigate back to your root project directory and type `npm start`. Requests should be directed to `http://localhost:3000`.

***

# Important Notes:

Currently, this will only accept GET and POST requests to the following urls: 
  * `GET` to /userlist
  * `POST` to /adduser
  
Other RESTful requests can be implemented by following the styles outlined by these initial patterns in the `routes/index.js` file and standard JS logic. Again, please reference the [tutorial](http://cwbuecheler.com/web/tutorials/2014/restful-web-app-node-express-mongodb/) from above for further reading. You can contact me directly at [brett.macy.codes@gmail.com](mailto:brett.macy.codes@gmail.com) with any questions about this project. Thanks!
