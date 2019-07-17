This is a webapplication written in node js, which counts the no.of visits happened on the site.
This makes use of redis as the in memory database for calculating the no.of visits.
To containerize this, there is a Docker file which specifies the steps to run the web application. The prerequisite for the webapplication to run is the redis server.
The Dockercompose.yml file first start the redis server and the the Dockerfile will be used to build and then start the application.
