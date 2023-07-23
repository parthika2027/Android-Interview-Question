1. **What are the access modifiers you know? What does each one do?**

Ans: There are four access modifiers in Java language (from strictest to the most lenient):

  a. **Private** variables, methods, constructors or inner classes are only visible to its' containing class and its' methods. This modifier is most commonly used, for example, to allow variable access only through getters and setters or to hide the underlying implementation of classes that user should not use and therefore maintain encapsulation. The Singleton constructor is also marked private to avoid unwanted instantiation from outside.

  b. **Default** (no keyword is used) This modifier can be applied to classes, variables, constructors and methods and allows access from classes and methods inside the same package.

  c. **Protected** can be used on variables, methods and constructors, allowing access only to subclasses and classes inside the same package as protected members' class.

  d. **Public** modifier is widely used on classes, variables, constructors, and methods to grant access from any class and method anywhere. It should not be used everywhere as it implies that data marked with the public is not sensitive and can not be used to harm the program.

2. **What is final in Java?**

Ans: Final is a keyword used to restrict the user in Java programming. It can be applied to variables, methods, or classes.

3. **Why do we need the final keyword in Java?**

Ans: Final keyword is used in Java program for three different purposes that are as follows:

a. To declare a constant or to stop the value change. For example, private final int const_value = 50;

b. To prevent inheritance. When a class is marked with final keyword, it cannot be subclassed. String, Integer, and other wrapper classes are examples of final classes.

c. To prevent a method from being overridden. When a method is marked with final keyword, it cannot be overridden by subclasses. A method declared with final keyword is faster than any other method because it is resolved at compile time.

4. **What is a blank final variable in Java?**

Ans: A variable that is declared as final and not initialized at the time of declaration is called a blank final variable.

5. **Difference between final, finally, and finalize**

| SL No. | Key | Final | Finally | Finalize |
| :---: | :---: | :---: | :---: | :-------: |
| 1 | Definition|final is the keyword  which is used to apply restrictions on a class, method or variable. | finally is the block in Java Exception Handling to execute the important code whether the exception occurs or not. | finalize is the method in Java which is used to perform clean up processing just before object is garbage collected. |
| 2 | Applicable to | Final keyword is used with the classes, methods and variables. | Finally block is always related to the try and catch block in exception handling. | finalize() method is used with the objects. | 
| 3 | Functionality | Once declared, final variable becomes constant and cannot be modified. final method cannot be overridden by sub class. final class cannot be inherited. | finally block runs the important code even if exception occurs or not. finally block cleans up all the resources used in try block | finalize method performs the cleaning activities with respect to the object before its destruction. |
| 4 | Execution | Final method is executed only when we call it. | Finally block is executed as soon as the try-catch block is executed. It's execution is not dependant on the exception | finalize method is executed just before the object is destroyed. |
