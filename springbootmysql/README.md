# Spring Project to test data access with mysql


- [Spring Guide](https://spring.io/guides/gs/accessing-data-mysql/)
- [Code Repo](https://github.com/spring-guides/gs-accessing-data-mysql)

1. run mysql db using docker
```docker run -d -p 3306:3306 --name=docker-mysql --env="MYSQL_ROOT_PASSWORD=test1234" mysql```
2. run app: ``` java -jar .\target\springbootmysql-0.0.1-SNAPSHOT.jar```
3. use command line to do a post: ```curl localhost:8080/demo/add -d name=First -d email=someemail@someemailprovider.com
   Saved```
4. see output using: http://localhost:8080/demo/all
5. you can see data getting in mysql db: 
   1. login: ```sudo mysql --password```
   2. query: ``` select * from user```