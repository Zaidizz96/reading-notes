# Spring App Basics

## What role do the @Controller classes play in a Spring MVC application?

- Role of @Controller classes in Spring MVC:

    - @Controller classes in Spring MVC control user requests.
    - They decide what should happen when a user interacts with a web page.
    - They handle things like clicking links or submitting forms.
    - They ensure the right code is run for different user actions.
  
## Explain to a non-technical friend what a GET request is?

Imagine the internet as a vast library filled with books (web pages). When you want to read a specific book (web page), you ask the librarian (the web server) for that book. You simply tell the librarian the title of the book you want, and the librarian gives it to you. In this case, the librarian doesn't need to change or modify the book; they just hand it over to you. This is similar to a GET request on the internet.

## What annotation should be placed on your Spring Boot application class?

By adding @SpringBootApplication to your main class, Spring Boot will automatically configure and bootstrap your application, making it ready to run as a Spring Boot application.

# Spring MVC and Thymeleaf

## What method allows for a variable defined in Java (in your Spring Controller) to be dispalyed in HTML with the help of Thymeleaf?

- To show a Java variable in HTML using Thymeleaf, use ${variableName} in your HTML template.
- Thymeleaf replaces ${variableName} with the actual Java variable value when rendering the HTML.

## Explain the role of a @Controller class in a Spring MVC application?

- In Spring MVC, a @Controller class manages user requests.
- It figures out what to do when a user interacts with a web page.
- It works with the application's logic (the model) and decides which web page to show.
- Think of it as the conductor of an orchestra, coordinating everything.

## What is a model attribute refered to in Thymeleaf?

1. A model attribute in Thymeleaf is a data variable.
2. It's set in the Spring Controller and represents backend data.
3. Thymeleaf lets you use these attributes in your HTML.
4. For example, ${user.name} displays a user's name in the HTML, blending data from Java code into web pages.

## Things I want to know more about

Dependency Injection.
Security
Request Mapping: