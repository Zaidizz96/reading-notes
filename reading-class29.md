# Room Database and DAO

This README provides an overview of the Room database, its underlying database engine, similarities to JPA, and the concept of a DAO (Data Access Object) in Android development.

## What Database Engine is Room Wrapped Around?

Room is a database library in Android that uses SQLite as its underlying database engine. SQLite is a lightweight, open-source, and self-contained relational database engine, making it a popular choice for mobile app development. The choice of SQLite as the database engine for Room is advantageous for many Android applications due to its simplicity, speed, and efficiency. However, the suitability of SQLite depends on the specific requirements of your app. While it's a good choice for many Android applications, larger and more complex systems might require alternative databases.

## Similarities Between Room and JPA

Room and Java Persistence API (JPA) share some similarities, although they are used in different contexts:

- **Platform**: JPA is primarily used in Java-based applications, while Room is designed for Android.

- **Annotation-Based**: Both Room and JPA use annotations to define entities, relationships, and queries.

- **Object-Relational Mapping (ORM)**: JPA is a general-purpose ORM framework, while Room is optimized for SQLite.

- **Database Engine**: JPA is versatile and can work with various database engines, whereas Room is tightly integrated with SQLite.

In summary, while Room and JPA share concepts, Room is tailored for Android development and optimized for SQLite.

## Data Access Object (DAO)

A Data Access Object (DAO) is a design pattern used to separate data access logic from the rest of an application. In Android development with Room, a DAO is an interface or class that provides an abstract API for interacting with the database. It defines methods for CRUD operations (Create, Read, Update, Delete) on the database entities.

A typical DAO consists of:

1. **Interface or Abstract Class**: DAOs are declared as interfaces or abstract classes, containing method signatures for database operations.

2. **Annotated Methods**: DAO methods are annotated with Room-specific annotations like `@Insert`, `@Query`, `@Update`, and `@Delete` to specify SQL queries or actions.

3. **Entity Type**: Each DAO is associated with a specific entity class, and its methods operate on instances of that entity.

Here's a simple example of a DAO for a "User" entity:

```java
@Dao
public interface UserDao {
    @Insert
    void insert(User user);

    @Query("SELECT * FROM users WHERE id = :userId")
    User getUserById(int userId);

    @Update
    void updateUser(User user);

    @Delete
    void deleteUser(User user);
}
