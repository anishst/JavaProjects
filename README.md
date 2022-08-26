# Java Projects

Practice java projects

## SimpleJSP

A simple java project based on JSP
        
### Run Local (under test)
1. build war file:  ```jar -cvf webapp.war *.*```
2. you will need to deploy to tomcat server..details to come

### Run with docker

1. go to SimpleJSP folder in command prompt:
```shell
# build image
docker build -t myjspapp .  
# run container
 docker run --rm -it -p 8888:8080 myjspapp
```
2. access app: http://localhost:8888/webapp/

