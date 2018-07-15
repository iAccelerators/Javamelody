# Javamelody

Step  1:
Please add below dependency in your Pom.xml

```xml
<dependency>
    <groupId>net.bull.javamelody</groupId>
    <artifactId>javamelody-core</artifactId>
    <version>1.73.1</version>
</dependency>  ```


Step 2 : 

Build your Application

Step 3:

Deploy the war file in tomcat server

Step 4:

Once application is deplyed and running, you can access the Montioring by below URL.

http://localhost:80XX/applicationContext/monitoring

In our case applicationContext is "javamelody"

/monitoring  ---> next to application context will take you to Monitoring Screen


