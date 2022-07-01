docker-compose up --scale application=2


it will start mysql, nginx and 2 instances of application.
nginx will load balance requests to 2 instances of application.