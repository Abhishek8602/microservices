# What is Spring 
The Spring Framework (Spring) is an open-source application framework that provides infrastructure support for developing Java applications. One of the most popular Java Enterprise Edition (Java EE) frameworks, Spring helps developers create high performing applications using plain old Java objects 

A framework is a large body of predefined code to which developers can add code to solve a problem in a specific domain. There are many popular Java frameworks including Java Server Faces (JSF), Maven, Hibernate, Struts, and Spring.

Released in June 2003 by Rod Johnson


# Why Spring?

Java programs are complex and feature many heavyweight components. Heavyweight means the components are dependent on the underlying operating system (OS) for their appearance and properties.

Spring is considered to be a secure, low-cost and flexible framework. Spring improves coding efficiency and reduces overall application development time because it is lightweight -- efficient at utilizing system resources -- and has a lot of support.

# Advantages of Spring Framework
There are many advantages of Spring Framework. They are as follows:

+ ### Predefined Templates
Spring framework provides templates for JDBC, Hibernate, JPA etc. technologies. So there is no need to write too much code. It hides the basic steps of these technologies.

Let's take the example of JdbcTemplate, you don't need to write the code for exception handling, creating connection, creating statement, committing transaction, closing connection etc. You need to write the code of executing query only. Thus, it save a lot of JDBC code.

+ ###  Loose Coupling
The Spring applications are loosely coupled because of dependency injection.

+ ### Easy to test
The Dependency Injection makes easier to test the application. The EJB or Struts application require server to run the application but Spring framework doesn't require server.

+ ### Lightweight
Spring framework is lightweight because of its POJO implementation. The Spring Framework doesn't force the programmer to inherit any class or implement any interface. That is why it is said non-invasive.

+ ### Fast Development
The Dependency Injection feature of Spring Framework and it support to various frameworks makes the easy development of JavaEE application.

+ ### Powerful abstraction
It provides powerful abstraction to JavaEE specifications such as JMS, JDBC, JPA and JTA.

# Dependency Injection

+ Invertion of Control



# Docker
![bg width:1000px](download.png)  

- Docker is a platform that enables developers to easily create, deploy, and run applications in containers.

- Containers are lightweight, portable, and self-contained environments that allow applications to run consistently across different operating systems and infrastructure.

- Docker provides a set of tools and services that make it easy to create and manage containers, including a container runtime, an image registry, and a container platform.



- containerization 

Docker uses containerization technology to create containers that can be run on any operating system or cloud infrastructure, making it easier to develop, test, and deploy applications across different environments. Each container is an isolated environment that runs a specific application and its dependencies, with its own filesystem, network, and resources.

- Docker images

Containers in Docker are created from Docker images, which are like snapshots of a specific configuration of an application and its dependencies. These images are used to create containers, and can be shared and reused by developers, allowing them to easily build and deploy applications in different environments. 


## Here are some advantages of using Docker:

- Portability: Docker containers are highly portable, meaning they can run consistently across different environments, including development, testing, and production.

- Resource efficiency: Docker allows you to run multiple containers on a single host, making better use of your system resources and reducing the cost of infrastructure.

- Rapid deployment: Docker containers can be deployed quickly and easily, allowing you to scale up or down as needed.

- Consistency: Docker ensures consistency across different environments by using the same container image for development, testing, and production.

- Isolation: Docker containers are isolated from each other and from the host system, ensuring that any issues with one container do not affect the others.

- Flexibility: Docker allows you to choose the tools and technologies that work best for your application, making it easy to experiment and iterate.

- Version control: Docker allows you to version control your container images, making it easy to roll back to a previous version if needed.

- Collaboration: Docker makes it easy to collaborate with other developers by providing a consistent environment that can be shared and reproduced.

- Security: Docker provides built-in security features that help protect your applications from external threats.

- Ecosystem: Docker has a large ecosystem of tools and services that can be used to build, test, and deploy applications.

## Here are some disadvantages of using Docker:

- Complexity: Docker can be complex to set up and configure, especially for users who are new to containerization.

- Limited Support: Docker is an open-source platform, which means that support is limited compared to proprietary software solutions.


