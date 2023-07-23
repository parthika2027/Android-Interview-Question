# OOPS

1. **What is Object Oriented Programming?**
2. **What is an object?**
3. **What is a class?**

 Java class is a set of object which shares common characteristics/ behavior and common properties/ attributes. There are certain points about Java Classes as mentioned below:
- Class is not a real-world entity. It is just a template or blueprint or prototype from which objects are created.
- Class does not occupy memory.
- Class is a group of variables of different data types and a group of methods.
A Class in Java can contain
- Data member
- Method
- Constructor
- Nested Class
- Interface

# Polymorphism

7. **What is Polymorphism**

Polymorphism is features of Object-Oriented Programming. Polymorphism allows us to perform a single tasks in different ways. In other words, polymorphism allows you to define one interface and have multiple implementations. The word “poly” means many and “morphs” means forms, So it means many forms.
Or
Polymorphism refers to the ability to exist in multiple forms. Multiple definitions can be given to a single interface. For example, if you have a class named Vehicle, it can have a method named speed but you cannot define it because different vehicles have different speeds. This method will be defined in the subclasses with different definitions for different vehicles

8. **What is static polymorphism?**

Ans: Static polymorphism (static binding) is a kind of polymorphism that occurs at compile time. An example of compile-time polymorphism is method overloading

9. **What is dynamic polymorphism?**

Ans: Runtime polymorphism or dynamic polymorphism (dynamic binding) is a type of polymorphism that is resolved during runtime. An example of runtime polymorphism is method overriding.

10. **What is method overloading?**

Ans: Method Overloading allows different methods to have the same name, but different signatures where the signature can differ by the number of input parameters or type of input parameters, or a mixture of both. Method overloading is also known as Compile-time Polymorphism, Static Polymorphism, or Early binding in Java. In Method overloading compared to the parent argument, the child argument will get the highest priority.

11. **What is method overriding?**

Ans: In Java, method overriding occurs when a subclass (child class) has the same method as the parent class. In other words, method overriding occurs when a subclass provides a particular implementation of a method declared by one of its parent classes

12. **Can we overload static methods?**

Ans: Yes, we can overload static methods, we can have two or more static methods with the same name but with different parameters.

# Abstractions

13. **What is Abstractions in Java?**

Ans: Abstraction in Java is a process of hiding the implementation details from the user and showing only the functionality to the user. It can be achieved by using abstract classes, methods, and interfaces

14. **What is Abstract Class?**

Ans: Java abstract class is a class that can not be initiated by itself, it needs to be subclassed by another class to use its properties. An abstract class is declared using the “abstract” keyword in its class definition.

15. **What is Abstract Method?**

Ans: A method that is declared as abstract and does not have implementation is known as an abstract method.
Eg: abstract void printStatus();//no method body and abstract

16. **What is Interface?**

Ans: Interfaces, on the other hand, are collections of abstract methods.

18. **How to achieve or implement Abstraction in Java?**

Ans: There are two ways to implement abstraction in java. They are as follows:
a) Abstract class (0 to 100%)
b) Interface (100%)

19. **Can an abstract method be declared static?** - No
20. **Can an abstract method be declared with a private modifier?**

Ans: No, it cannot be private because the abstract method must be implemented in the child class. If we declare it as private, we cannot implement it from outside the class.

21. **What is the Concrete method in Java?**

Ans: A concrete method in Java is a method that has always the body. It is also called a complete method in Java.

22. **When to use Abstract class in Java?**

Ans: An abstract class can be used when we need to share the same method with all non-abstract sub-classes with their own specific implementations.

23. **When to use the Abstract method in Java?**

Ans: An abstract method can be used
a) When the same method has to perform different tasks depending on the object calling it.
b) When you need to be overridden in its non-abstract subclasses.

24. **Is it possible to create an object of abstract class in Java?**

Ans: No. It is not possible but we can create an object of its subclass.

25. **What will happen if we do not override all abstract methods in subclass?**

Ans: Java compiler will generate compile time error. We will have to override all abstract methods in subclass.

26. **What is the advantage of Abstract class in Java?**
27. **Can We Create Instance Of Interface?**

Ans: No, we cannot create object of both an interface and abstract class.

28. **Can We Declare Abstract Method As Static?**

Ans: No, we can't use static keyword with abstract method.

29. **Can We Declare the Abstract Method As Final?** - No
30. **Can We Declare Abstract Method As Private?** - No

# Encapsulation

31. **What is Encapsulation?**

Ans: Encapsulation in Java is one of the main components of object-oriented programming (OOP). It refers to the process of securing methods and data into a single unit. Encapsulation also has the name "data hiding" because it involves data that is not directly accessible to any user. 

32. **How to achieve encapsulation in Java? Give an example**

Ans: There are two key points that should be kept in mind to achieve the encapsulation in Java. They are as follows:
- Declare the variable of the class as private.
- Provide public setter and getter methods to modify the values of variables.

33. **Difference between Abstraction and Encapsulation?**

Ans: There are the following differences between Abstraction and Encapsulation:
a) Abstraction solves the problem at the design level whereas encapsulation solves the problem at the implementation level.
b) Abstraction is implemented in Java using Interface and Abstract class whereas encapsulation is implemented using private and protected access modifiers.
c) Abstraction is used to hide unwanted data and giving relevant data whereas encapsulation is used for hiding data and code in a single unit to prevent access from outside.

34. **Can we achieve abstraction without encapsulation in Java?** - Yes
35. **What are the benefits of Encapsulation?**

The main benefit of encapsulation is the ability to modify the implemented code without breaking the code of others who use our code. It also provides us with maintainability, flexibility and extensibility to our code.


# Inheritance

36. **What is Inheritance?**

Ans: Inheritance is a feature of OOPs that allows classes to inherit common properties from other classes. For example, if there is a class such as ‘vehicle’, other classes like ‘car’, ‘bike’, etc can inherit common properties from the vehicle class. This property helps you get rid of redundant code thereby reducing the overall size of the code.

Ans: Inheritance is an important pillar of OOP(Object-Oriented Programming). It is the mechanism in Java by which one class is allowed to inherit the features(fields and methods) of another class. In Java, Inheritance means creating new classes based on existing ones. A class that inherits from another class can reuse the methods and fields of that class. In addition, you can add new fields and methods to your current class as well. 
Super Class/Parent Class: The class whose features are inherited is known as a superclass(or a base class or a parent class).
Sub Class/Child Class: The class that inherits the other class is known as a subclass(or a derived class, extended class, or child class). The subclass can add its own fields and methods in addition to the superclass fields and methods.
Reusability: Inheritance supports the concept of “reusability”, i.e. when we want to create a new class and there is already a class that includes some of the code that we want, we can derive our new class from the existing class. By doing this, we are reusing the fields and methods of the existing class.

37. **What are the different types of inheritance?**

- Single inheritance
- Multiple inheritance
- Multilevel inheritance
- Hierarchical inheritance
- Hybrid inheritance

38. **What is a superclass?**

Ans: A superclass or base class is a class that acts as a parent to some other class or class. For example, the Vehicle class is a superclass of class Car

39. **Why Do We Need Java Inheritance?**

Ans: Code Reusability: The code written in the Superclass is common to all subclasses. Child classes can directly use the parent class code. 
Method Overriding: Method Overriding is achievable only through Inheritance. It is one of the ways by which Java achieves Run Time Polymorphism.
 Abstraction: The concept of abstract where we do not have to provide all details is achieved through inheritance. Abstraction only shows the functionality to the user.

40. **How is Inheritance implemented/achieved in Java?**

Ans: Inheritance can be implemented or achieved by using two keywords: extends: extends is a keyword that is used for developing the inheritance between two classes and two interfaces. 
implements: implements keyword is used for developing the inheritance between a class and interface.

41. **Are static members inherited to subclass in Java?**
42. **Can we extend (inherit) final class?** - No
43. **Can a final method be overridden?** - No
44. **How will you restrict a member of a class from inheriting its subclass?**
45. 
