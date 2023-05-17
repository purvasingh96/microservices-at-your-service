# Microservices at your service! 👾

##  Implementing Service Registry using Eureka Server 🍀
1. Create a `maven-scala-seed` project in your VS Code.
2. Leverage the `pom.xml` file which has the latest related dependencies. Then, build the project.
3. `application.yml` has related configurations such as port etc, which is crucial so that our server doesn't try to register with itself.
4. Be extra careful while installing the correction version of dependencies.
5. References:<br>
  a. https://start.spring.io/ <br>
  b. https://mvnrepository.com/artifact/org.codehaus.jettison/jettison/1.2 <br>
  c. https://www.youtube.com/watch?v=yKZVdkrTBTg&ab_channel=LearnCodeWithDurgesh <br>
  
### Eureka Dashboard
Once your project is up and running, visit the following link: http://localhost:8761/ and your eureka dashboard (with currently no instances registered with Eureka) should look as below:
![eureka-dashboard-1](https://github.com/purvasingh96/microservices-at-your-service/blob/master/img/eureka-dashboard-empty-1.png)
![eureka-dashboard-2](https://github.com/purvasingh96/microservices-at-your-service/blob/master/img/eureka-dashboard-empty-2.png)

