# MVC, MVP, MVVM

1. **What is MVVM?**
Ans: Model — View — ViewModel (MVVM) is the software architecture pattern that overcomes all drawbacks of MVP and MVC design patterns. MVVM suggests separating the data presentation logic(Views or UI) from the core business logic part of the application
The separate code layers of MVVM are
Model: This layer is responsible for the abstraction of the data sources. Model and ViewModel work together to get and save the data.
View: The purpose of this layer is to inform the ViewModel about the user’s action. This layer observes the ViewModel and does not contain any kind of application logic.
ViewModel: It exposes those data streams which are relevant to the View. Moreover, it serves as a link between the Model and the View.

2. **Ways to Implement MVVM in the Project**

Ans: There are 2 ways to implement MVVM design pattern in Android projects:
Using the DataBinding library released by Google
Using any tool like RxJava for DataBinding.