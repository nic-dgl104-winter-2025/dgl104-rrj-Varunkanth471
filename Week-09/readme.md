# Design Patterns

## Introduction

Design patterns are reusable fragments of code that provide solutions to well-understood coding problems. While they do not perform specific functions on their own, they help create maintainable and scalable code. These patterns are widely recognized by experienced programmers, improving code readability and long-term maintainability.

## Key Concepts

### What Are Design Patterns?

- Reusable solutions to common programming problems.
- Not actual code, but structured approaches to problem-solving.
- Improve code maintainability and readability.
- Recognizable by developers, making collaboration easier.


# Activities Completed
## Four Common Design Patterns

### 1. Singleton Pattern

- **Purpose:** Ensures that a class has only one instance and provides a global point of access to it.
- **Use Case:** When you want to restrict the instantiation of a class to one object.
- **Example:** Database connections or logging classes where a single instance is needed throughout the application.
  
### 2. Factory Method Pattern

- **Purpose:** Defines an interface for creating an object, but allows subclasses to alter the type of objects that will be created.

- **Use Case:** When a class cannot anticipate the class of objects it must create or wants its subclasses to specify the objects it creates.

- **Example:** UI frameworks where different types of buttons (like Windows or MacOS) are created depending on the platform.  

### 3. Observer Pattern
- **Purpose:** Allows a subject to notify its observers of any state changes without knowing who or what those observers are.

- **Use Case:** When you need to implement a subscription mechanism to allow multiple objects to listen to and react to events or state changes from another object.

- **Example:** Implementing a real-time chat application where new messages are broadcasted to multiple users.

### 4. Strategy Pattern
- **Purpose:** Defines a family of algorithms and allows them to be interchangeable. This pattern allows the algorithm to be selected at runtime.

- **Use Case:** When a class has multiple methods for performing an action and needs to switch between them dynamically.

- **Example:** Sorting strategies where different sorting algorithms can be used based on input size or data characteristics.



