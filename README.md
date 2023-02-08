## Weather forecast 

### Overall description 
The whole project so far consists of the following services: 
* Database (MongoDB)
* The database filler, which is supposed to run once in order to fill the db with the historical data 
* Server written in Flask, responsible for handling http requests 
* Pipline (the core of the whole project), scrapes online data once a day, (re)trains an ML model, infers incoming data

Each service runs in a separate Docker contianer. To assemble the project, just type `docker-compose up` in the project's directory. 

Here is a more detailed explanation of the services mentioned 
