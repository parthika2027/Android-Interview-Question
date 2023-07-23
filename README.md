# Android-interview-questions

## Java
* [Core Java](#core-java)
* [OOPS](#oops)
* [Collections](#collections)
* [Singleton Class](#singleton-class)
* [](#)
* [](#)

## Android
* [Core Android](#core-android)
* [MVP MVC MVVM](#mvp-mvc-mvvm)
* [Thred MultiThred AsyncTask](#thred-multithred-async-task)
* [Activity and Fragment](#activities-fragments)
* [View and ViewGroups](#)
* [Intent and Broadcasting](#)
* [Services](#services)
* [Battery Life Optimizations](#)
* [Permissions](#permissions)
* [Work Manager](#work-manager)
* [Android Jetpack](#android-jetpack)
* [API Call](#api-call)
* [Room DB](#room-db)
* [Google Map](#google-map)
* [Push Notification](#push-notification)
* [Version Control](#version-control)
* [Percelable and Serializable](#)
* [Firebase Auth](#firebase-auth)
* [AIDL](#aidl)
* [Intercepter](#intercepter)
* [Android Architechture](#android-architechture)
* [Kotlin Coroutines](#kotlin-coroutines)
* [Data Structure and Algorithms](#data-structure)
* 
### Core Java

* **What are the access modifiers you know? What does each one do?**

Ans: There are four access modifiers in Java language (from strictest to the most lenient):
  - private variables, methods, constructors or inner classes are only visible to its' containing class and its' methods. This modifier is most commonly used, for example, to allow variable access only through getters and setters or to hide the underlying implementation of classes that should not be used by user and therefore maintain encapsulation. The Singleton constructor is also marked private to avoid unwanted instantiation from outside.
  - Default (no keyword is used) this modifier can be applied to classes, variables, constructors and methods and allows access from classes and methods inside the same package.
  - protected can be used on variables, methods and constructors therefore allowing access only to subclasses and classes that are inside the same package as protected members' class.
  - public modifier is widely-used on classes, variables, constructors and methods to grant access from any class and method anywhere. It should not be used everywhere as it implies that data marked with public is not sensitive and can not be used to harm the program.


### Core Android

Android Interview Questions:

#### Base


#### Activity and Fragment

* **What is `Activity` and its lifecycle?**

* **What is `Activity's` lifecycle?**
  
* **What is `Fragment` and its lifecycle.**

* **What is the difference between FragmentPagerAdapter vs FragmentStatePagerAdapter?**
    - FragmentPagerAdapter: Each fragment visited by the user will be stored in the memory but the view will be destroyed. When the page is revisited, then the view will be created not the instance of the fragment.
    - FragmentStatePagerAdapter: Here, the fragment instance will be destroyed when it is not visible to the user, except the saved state of the fragment.


### Services
