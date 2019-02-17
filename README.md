# DOF Exam 2019.02.10 / 2019.02.17
Exam Repository for DevOps Fundamentals Course @ SoftUni

Set of three Docker containters each with dedicated role - php, redis, and nginx, that form a simple web application.

For a successful completion you have to:
 - (re)build the images;
 - (re)push the images;
 - (re)run the containers;
 - (re)apply the changes on the running application;

Please note that:
 - the **app** folder must be mounted where (in terms of path and images) applicable;
 - each container should be named after the following rule - **role-host**, where role is *php*, *redis*, or *nginx*;
 - mind the ports - each one is listening on a specific port, for example nginx is set to listen on port **80**;
 - php files are expected to be in the **/site** folder of both nginx and php containers;
 - nginx container should be started after php;

Use docker-compose.yml file as a starting point when building the final set of application configuration files for the platform of your choice. You can use a tool and then modify them, or do the entire process manually. 
