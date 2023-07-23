#Singleton Class

1. **What is Singleton Class?**

Ans: The singleton pattern is a design pattern that restricts the instantiation of a class to one object.
- Make a constructor private.
- Write a static method that has the return type object of this singleton class. Here, the concept of Lazy initialization is used to write this static method.

2. **Purpose of Singleton Class?**
Ans: The primary purpose of a Java Singleton class is to restrict the limit of the number of object creations to only one. This often ensures that there is access control to resources, for example, socket or database connection.
Memory space wastage does not occur with the use of the singleton class because it restricts instance creation. As the object creation will take place only once instead of creating it each time a new request is made.
