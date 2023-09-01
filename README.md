# Flutter_interview_Quiz
# SOLID Principles
- Acroname for Five Object Oriented Design principles by uncle Bob, intended to to guid software developers in creating a more flexible, maintainable and scallable apps. 

* S - Single Responsibility principle
    - This states that a class should only be responsible for one thing

* O - Open Closed
    - This states that for a good practice, you should be able to add new features without modifying the existing code.
    - In otherwords, an entinty should be open for extensions but closed for modification.

* L - Liskov Substitution Principle
    - This states that some classes should be substitutable from the classes that they were derrived from. e.g. If class B is a subtype of class A, then class a can be replicated with the object of type class B without changing or breaking the behaviour of the program.

* I - Interface Segregation Principle
    - This principle states that cliants do not have to impliment the behaviour they do not need. This encourages them to create interfaces with minimal methods.

* D - Dipendancy Inversion 
    - This principle states that the high level module must not depend on the low level module, but they should depend on the obstractions. This principle allows for decoupling.


# Types of Code Architectures 
- This basically means how you structure your codebase to allow separation of concerns

* Flutter Vanilla
- This is the simplest architecture where you build your app using the default Flutter framework without any specific architectural pattern. It works well for small applications or when you're prototyping, but it can become hard to maintain and scale as the app grows.

* MVC Architecture (Model-View-Controller)
-  MVC is a traditional architectural pattern that separates the application into three main components: the model (data and business logic), the view (UI), and the controller (mediates between the model and the view). While Flutter doesn't provide explicit support for MVC, you can implement this pattern manually.

* MVVM Architecture(Model-View-ViewModel)
- MVVM is another popular architectural pattern that separates the app into three components: the model (data and business logic), the view (UI), and the view model (intermediary between the model and the view). Flutter doesn't have native support for MVVM, but you can achieve it using third-party packages like provider or mobx

* BLoC (Business Logic Component)
-  BLoC is a Flutter-specific architectural pattern that uses streams to manage the flow of data and events within an application. It separates the app into three main components: the UI (view), the business logic (BLoC), and the data layer (repository). BLoC is built on top of the dart:async package and is widely used in the Flutter community.

* Clean Architecture
- Clean Architecture is an architectural pattern that enforces separation of concerns and dependency inversion principles. It divides the app into different layers such as presentation, domain, and data, each with its own responsibilities. Clean Architecture is not specific to Flutter but can be implemented in Flutter apps.


# 

# Design Pattern aprroaches 
- Design patterns are general reusable solutions to common software design problems. They provide proven ways to structure code, organize components, and handle interactions between different parts of your application. Design patterns focus on improving the overall architecture, maintainability, and scalability of your codebase. 
- Some common design patterns include Singleton, Factory Method, Observer, Composite, and more. These patterns are applicable to various aspects of software development beyond just state management.

#

# State Management 
- This refers to techniques used to manage the UI's state and keep it in sync with the underlying data.
- there are different techniques of managing state in Flutter, like:
    > setState()
    > BloC 
    > Redux
    > Riverpod

#

#