# Spring Data JPA Reading Assignment

## How are query methods defined when using Spring Data JPA?

Query methods in Spring Data JPA are defined by creating method signatures in a repository interface. The method names follow a specific naming convention that allows Spring Data JPA to generate the appropriate SQL queries. Typically, you start the method name with "findBy," "getBy," "readBy," or "queryBy," followed by the property or properties you want to use for filtering records. For example, if you have an entity called `User` with a property `username`, you can define a query method like this:

```
java

User findByUsername(String username); 
```
## Which dependencies will you need in order to complete the Spring guide?
- `spring-boot-starter-data-jpa`: for Spring Data JPA support.
- `javax.persistence`: for JPA annotations and functionality.
- A database driver dependency for your chosen database (e.g., `spring-boot-starter-data-h2` for H2 database).

## What annotations are used to specify an auto generated identification number for an Entity?
To specify an auto-generated identification number (usually the primary key) for an Entity in Java Persistence API (JPA), you use the `@Id` and `@GeneratedValue` annotations. 

# Baeldung: Comparing repositories 

## Which of the Spring Data Repositories covered in the readings has the most methods available to it?
The `JpaRepository` interface from Spring Data JPA typically has the most methods available among the Spring Data repositories.
It provides a wide range of methods for common CRUD (Create, Read, Update, Delete).

## Name a downside of a Spring Data Repository.
One downside of Spring Data Repositories is that they can generate a large number of query methods based on naming conventions. While this can be convenient, it can also lead to "method explosion" when dealing with complex entity models.

## How would you define an operation to find a student based on their name in a repo named StudentRepository which extends JpaRepository?
you can follow the Spring Data JPA naming convention for query methods. Assuming your Student entity has a property called `name`

```
java
public interface StudentRepository extends JpaRepository<Student, Long> {
    Student findByName(String name);
}
```





  