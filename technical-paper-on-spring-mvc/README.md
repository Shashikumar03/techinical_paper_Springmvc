# Spring MVC framework

Hello readers, Thankyou for giving me time, It would take 5 mins of read, please enjoy yourself the article.

A Spring MVC is a Java framework which is used to build web applications. It follows the Model-View-Controller design pattern.

It implements all the basic features of a core spring framework like Inversion of Control, Dependency Injection.
The framework can be defined as a structure where we can find solutionof the various technical problems. 
Spring Framework is an application framework and inversion of control container for the Java platform.

## SPRING-Modules

The Spring Framework includes several modules
that provide a wide variety of services. They are: 

    1.  Spring Core Container
        * This is the base module of Spring. It provides various spring containers.
    2.  Aspect-oriented programming
        * Enables implementing cross- cutting concerns.
    3.  Authentication and authorization
        * These are the configurable security processes that support a range of standards, protocols,tools and practices.
    4.  Convention over configuration
        * A rapid application development solution for Spring-based enterprise applications.
    5.  Data access
        * Working with relational database management systems on the Java platform using JDBC and object-relational mapping tools and with NoSQL 
    6.  Transaction management
        * Unifies several transaction management APIs and coordinates transactions for Java objects.
    7.  Testing
        * Support classes for writing unit tests and integration tests    
![spring framework runtime](images\Capture1.PNG)
## Spring-IOC and Dependency Injection
These are the design patterns that are used to remove dependency from the programming code. They make the code easier to test and maintain.
   
    1.  Dependency Injection
        * This is a design pattern that removes the dependency from the programming code so that it can be easy to manage and test the application. Dependency Injection makes our programming code loosely coupled. 
        # Advantages of Dependency Injection
        * Makes the code loosely coupled so easy to maintain
        * Makes the code easy to test
    2.  Inversion of Control
        * This provides a consistent means of configuring and managing Java objects using reflection. The IOC container is responsible for managing object lifecycles of specific objects , creating these objects, calling their initialization methods, and configuring these objects by wiring them together   
        * IOC makes the code loosely coupled. In such case, there is no need to modify the code if our logic is moved to new environment. In Spring framework, IOC container is responsible to inject the dependency. We provide metadata to the IOC container either by XML file or annotation. Inversion of Control
    
## MVC- Design & its Architecture
   MVC basically stands for the Model View Controller.It is a software architectural pattern for implementing user interfaces. 
   ####  The three components of the MVC are
    1.  Model 
        * Which encapsulates the application data and in general they will consist of POJO classes. 
    2.  View   
        * Which is responsible for rendering the model data and in general it generates HTML output that the client's browser can interpret 
    3.   Controller  
        * is responsible for processing user requests and building appropriate model and passes it to the view for rendering  

![mvc components](images\Capture2.PNG)
### Advantages of Spring Framework        

    * Predefined Templates
    * Loose Coupling
    * Lightweight
    * Fast Development


For more details on Spring MVC please visit [click here](https://www.javatpoint.com/spring-mvc-tutorial#:~:text=A%20Spring%20MVC%20is%20a,Inversion%20of%20Control%2C%20Dependency%20Injection.)
