# springboot-react
This is My fisrt  test programming skills for springboot-react (Java) i have never tried it before i will start go deep with Java and enjoy the good thing of java.
Here i have Rest API to create, retrieve and delete orders. If a user has ADMIN role he/she can also retrieve information of other users or delete them.
order-api stores its data in Postgres database you can use any database 
I also have ReactJS frontend application where a user with role USER can create an order and retrieve a specific order. On the other hand, a user with role ADMIN as access to all secured endpoints.
To go through this you must have the followin installed to your Pc 
npm
Java 17+
Docker
Docker-Compose
jq
Then to Start:- your app
n a terminal, make sure you are inside springboot-react root folder
Run the following command to start docker-compose containers
docker-compose up -d

Running order-app using Maven & Npm
order-api

Open a terminal and navigate to springboot-react/order-api folder

Run the following Maven command to start the application

./mvnw clean spring-boot:run


order-ui

Open another terminal and navigate to springboot-react/order-ui folder

Run the command below if you are running the application for the first time

npm install
Run the npm command below to start the application

npm start

Applications URLs
order-api	http://localhost:8080/swagger-ui.html
order-ui	http://localhost:3000
Open a browser and access http://localhost:8080/swagger-ui.html.

The user credentials username and password(user user for both)

