# RESTfulservice-using-docker-springboot
This repository is on RESTful service using Docker and Spring Boot. For the front end I have used HTML, Jquery and Ajax to display data from Json.

## Files Included
1. RestAPI folder which has the Spring Boot application and the Docker file.
2. It also consists of HTML file (UI)
## About the application
This is a Spring Boot application with a hardcode Json data (Customer.json) and it consists of 4 GET API methods.

We then create a Docker file and build and run it to create a Docker Container which will fetch us the above data.

Then we use a webpage (simple front end UI) to show the endpoints in action.

### Following steps are followed to run the application

1. First build the docker file by using command
### `docker build -t anyname .` (It can be anyname after -t)

2. Then run the docker file by using the command
### `docker run -it -p 8081:8081 anyname` ( the name that you gave after -t)

After this the docker file is ready and running

Now just open the service.html file and the code should be running as expected.


