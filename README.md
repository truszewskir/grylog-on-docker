# Grylog on docker

Configuration for the simple launch of a working Graylog application. It include Mongo and Elastic dependencies. 

Type
```docker-compose up```
and enjoy

After login, you have to configure an input, for instance, GELF UDP. 
Chose System/Inputs/Launch new input. 

For more see the documentation 
http://docs.graylog.org/en/2.4/pages/installation/docker.html 
and 
https://hub.docker.com/r/graylog/graylog/
