# Hello World web application

Creating a simple web application on *Java* in various ways:

1. HTTP Servlet (`web.xml` file)
1. HTTP Servlet (*@WebServlet* annotation)
1. HTTP Servlet (*ServletContainerInitializer* interface implementation)
1. Spring MVC (`web.xml` file)
1. Spring MVC (*Java* configuration)
1. Spring Boot (Spring MVC)
1. Spring Boot (Spring WebFlux)
1. JavaServer Faces (Apache MyFaces)
1. JavaServer Faces (Oracle Mojarra)
1. GWT
1. Struts
1. Dropwizard
1. Wicket

## Requirements

* [JDK 8+](http://www.oracle.com/technetwork/java/javase/downloads/index.html)
* [Apache Maven 3.5.0+](https://maven.apache.org/download.cgi)

## Running

1. Change directory:
    `cd <maven module directory>`

1. From the command line with Maven:

    `mvn jetty:run`  
    (for *helloworld-web-servlet-xml*, *helloworld-web-servlet-annotation*, *helloworld-web-servlet-java-war*, *helloworld-web-spring-mvc-xml*, *helloworld-web-spring-mvc-java*, *helloworld-web-jsf-myfaces*, *helloworld-web-jsf-mojarra*, *helloworld-web-struts*, *helloworld-web-wicket* modules)

    `mvn spring-boot:run`  
    (for *helloworld-web-spring-boot-mvc*, *helloworld-web-spring-boot-webflux* modules)

    `mvn gwt:codeserver`  
    (in one terminal window for *helloworld-web-gwt-client* module)  
    `mvn jetty:run`  
    (in another terminal window for *helloworld-web-gwt-server* module)    

1. Access the deployed web application at: http://localhost:8080