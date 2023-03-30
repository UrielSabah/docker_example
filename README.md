# Docker Flask example

Work only to localhost
After creating the flask app
Update requirements using:
$ python3 -m pip freeze > requirements.txt 
Then create the dockerfile and update it
Then Build the docker container 
$ docker build --tag dockerapp .   
Then run the docker image
$docker run -d -p 8000:5000 dockerapp

