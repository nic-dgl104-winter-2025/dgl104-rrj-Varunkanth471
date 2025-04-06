# MV* Architectural Patterns

## Lecture notes/Key Points

### Definition of MV*
- MV* refers to a family of UI architecture patterns that use **Model** and **View** as core components.
- Common patterns include:
  - **MVC**: Model-View-Controller
  - **MVVM**: Model-View-ViewModel
  - **MVP**: Model-View-Presenter
  - **MVI**: Model-View-Intent

- **MVC**:
  - Originated in the 1970s with Smalltalk at Apple.
  - Influenced Objective-C and Swift for iOS development.
  - Was the de facto standard for iOS apps until recently.
- **MVVM**:
  - Gained prominence with modern frameworks like SwiftUI (iOS) and Jetpack Compose (Android).
  - Older web frameworks (e.g., Django, Ruby on Rails) still favor MVC.

- All MV* patterns are **GUI-focused** (graphical user interface).

### Usage

- **MVC**: Common in older web frameworks (Django, Ruby on Rails).
- **MVVM**: Popular in modern mobile apps (SwiftUI, Jetpack Compose).
- **MVP/MVI**: Alternatives used in Android before MVVM rose.
- MVVM frameworks for the web are gaining interest but lack traction.


## MVC (Model-View-Controller)

- UI architecture pattern with Model, View, and Controller.
- GUI-driven, separates concerns for testability.
- Presents data, no storage/processing.
- Handles user events, updates Model, adjusts View.
- User interacts with View → Controller captures events → Updates Model → Model notifies Controller → Controller updates View.
- Common in web frameworks.
- Less common in modern mobile apps.

## Model-View-ViewModel (MVVM)

- UI-based architectural pattern, similar to MVC, emphasizes data binding.
- Contains business logic and data and handles UI representation which represents a bridge to model and view, no to direct view reference.
- **Data Binding** 
  - Reduces boilerplate code, improves efficiency.
- Ideal for real-time data updates.
- Common in modern Android (Jetpack Compose), SwiftUI, and web frameworks (Vue, Angular, React).  

