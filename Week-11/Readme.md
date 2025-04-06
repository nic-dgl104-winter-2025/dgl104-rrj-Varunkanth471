# Object-Oriented Programming

- Object-Oriented Programming (OOP) is a way of writing computer programs using "objects." An object is like a container that holds information (called data or attributes) and instructions (called methods) for what it can do.
- https://www.youtube.com/watch?v=IWIdoBqLVeo an explanation/ overview about OOP.

## Key Concept

- **Classes:**
  - Blueprints for objects, define properties and methods.
  - Objects are instances of classes, customizable.
- **Encapsulation:**
  - Hides data/methods within classes (e.g., using `private`).
  - Prevents unexpected external modifications.
- **Inheritance:**
  - Classes inherit data/methods from parent classes.
  - Enables hierarchies (parent/subclasses) for focused designs.
  - Access levels: `private`, `public`, `protected`.
- **Polymorphism:**
  - Objects can act as instances of multiple classes (e.g., parent/grandparent).
  - Allows flexible treatment based on context.

- A brief discussion about **Encapsulation**,**Inheritance** and **Polymorphism**
  - https://pythonnumericalmethods.studentorg.berkeley.edu/notebooks/chapter07.03-Inheritance-Encapsulation-and-Polymorphism.html

# Programming Paradigms

- **Paradigm:**
  - Way to classify languages by features.
- **Imperative Paradigm:**
  - Includes OOP.
  - Specifies how to compute (e.g., control flow: `if`, `loops`).
- **Declarative Paradigm:**
  - Includes Functional Programming.
  - Specifies what to do, not how (no control flow).
  - Used in modern UI frameworks (e.g., Jetpack Compose, SwiftUI).
- **Prototypal Paradigm:**
  - Used in JavaScript, defines objects via prototypes, not classes.

# SOLID Design Principles and DRY Code in OOP

SOLID is an acronym representing five key design principles for creating maintainable and scalable software. These principles were popularized by Robert C. Martin around 2000 and continue to be highly relevant today.

- S: Single Responsibility Principle (SRP)

- The concept of SRP is to ensure that a class is focused on a single task, the code becomes easier to understand, test, and maintain. It also prevents unintended side effects since changes to one responsibility do not affect others.

- O: Open-Closed Principle (OCP)
 - should be open for extension but closed for modification.
 -  should be added by extending existing code (via inheritance, composition, etc.) rather than altering the original source. This protects existing functionality from bugs when new features are added.

- I: Interface Segregation Principle (ISP)
 - one general-purpose interface 