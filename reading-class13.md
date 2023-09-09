
# Spring related data One To Many relation 

## Name a few real-life examples of “One To Many” relationships:

    - Students and Courses: One student can enroll in many courses.
    - Author and Books: An author can write multiple books.
    - Department and Employees: A department can have multiple employees working in it.
    - Parent and Children: One parent can have multiple children.

## Given two entities, one named Player and one named Team, if you wanted to create a one-to-many relationship with those entities which would be the one and which would be the many?

In this case, the "Team" entity would typically be the "one," and the "Player" entity would be the "many." This means that one team can have many players, establishing a one-to-many relationship.

## Explain one-to-many relationships to a non-technical friend:

A one-to-many relationship is like a parent-child relationship in real life. Imagine a family where one parent can have multiple children. The parent is responsible for taking care of the children, and each child belongs to that parent. Similarly, in data, we can have one entity (the parent) associated with multiple related entities (the children). For example, one team can have multiple players. This relationship helps organize and manage data efficiently, just like how parents manage their children.

--- 

# Baeldung: Spring Integration Testing

## Describe the difference between a unit test and an integration test:

`Unit Test`: A unit test focuses on testing individual components or functions of a program in isolation. It verifies that each part of the code works correctly on its own, typically using mock objects or stubs for dependencies.
Integration Test: An integration test checks how different components or modules of a system work together. It tests the interactions between these components and ensures that they integrate correctly. Integration tests are broader in scope compared to unit tests.

## What is the object that provides support for Spring MVC Testing?

The object that provides support for Spring MVC Testing is the MockMvc object. It allows you to perform HTTP requests and validate the responses within your Spring MVC application without the need to deploy it to a server.

## What does the “perform()” method do in a Spring integration test?

In a Spring integration test using MockMvc, `the perform()` method is used to simulate an HTTP request to a specific endpoint (e.g., a controller's method). It sends an HTTP request with the specified parameters, such as HTTP method, request URI, and request parameters, to your Spring application. After performing the request, you can use other methods to assert and verify the response, making it a crucial part of testing the behavior of your Spring MVC controllers.
