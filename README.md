**Mad Mike Automobile Shops Car Management System**

Problem Statement Mad Mike has contracted you to build him a system to keep track of the cars that come into his many shops. Mike has 48 shops in four states. He needs to know certain things about each car for liability and government compliance issues.
VIN Plate #, State Make/Model Year Owners Name, Address and DL Number

He would also like to keep a record of A description of the problem Time the car was in the shop (day in, day out) Which workers worked on the car

He doesn’t want to host servers everywhere so you need to make this project cloud based. Specifically it needs to run in docker containers using docker-compose, so we can deploy it on AWS, Asure, etc….

At each of his shops, an employee would enter the information into a web browser, and it would submit to the host in AJAX form using HTTP and a RESTful interface.

So the main resource we are concerned with is the Automobile. So we need to Add a new car to the shop -> POST /cars
Update a car in the shop -> PUT /cars/:id Get a car in the shop -> GET /cars/:id Get all cars in the shop -> GET /cars/ Remove a car from the shop -> DELETE /cars/:id

Steps to Run the application:

1. Have docker installed in the machine

2. Clone the project
   
3. Open terminal with the downloaded project location

4. Type command - docker-compose up -d (note: by default docker compose is installed in mac and windows while installing docker. If you are running linux, install docker compose separate.)
Now the project is deployed. we can test the api's and the application

5. Go to the browser and access the URL http://localhost:3000/ to access the web React application.
   
6. The api's are accessible at the url http://localhost:8000/
   
7. Please refer to the API's for the automobile project https://documenter.getpostman.com/view/5309064/2s93sjV9Fj
