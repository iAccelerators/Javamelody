

# Why JavaMelody

```xml

The goal of JavaMelody is to monitor Java or Java EE applications in QA and production environments. 
It is not a tool to simulate requests from users, it is a tool to measure and calculate statistics on real 
operation of an application depending on the usage of the application by users.

JavaMelody is easy to integrate in most applications and is lightweight (no profiling and no database).
JavaMelody is mainly based on statistics of requests and on evolution charts.

It allows to improve applications in QA and production and helps to:
•	give facts about the average response times and number of executions
•	make decisions when trends are bad, before problems become too serious
•	optimize based on the more limiting response times
•	find the root causes of response times
•	verify the real improvement after optimizations

It includes summary charts showing the evolution over time of the following indicators:

•	Number of executions, mean execution times and percentage of errors of http requests, sql requests, 
jsf actions, struts actions, jsp pages or methods of business façades (if EJB3, Spring or Guice)
•	Java memory
•	Java CPU
•	Number of user sessions
•	Number of jdbc connections

These charts can be viewed on the current day, week, month, year or custom period.

```

# More details 

Home : https://github.com/javamelody/javamelody/wiki

Charts : https://github.com/javamelody/javamelody/wiki/Screenshots#charts

# Javamelody Setup

```xml


Step  1:
Please add below dependency in your Pom.xml


<dependency>
    <groupId>net.bull.javamelody</groupId>
    <artifactId>javamelody-core</artifactId>
    <version>1.73.1</version>
</dependency>  

```


Step 2 : 

Build your Application

Step 3:

Deploy the war file in tomcat server

Step 4:

Once application is deplyed and running, you can access the Montioring by below URL.

http://localhost:80XX/applicationContext/monitoring

In our case applicationContext is "javamelody"

/monitoring  ---> next to application context will take you to Monitoring Screen





