[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/MMj2nZMu)
# Rsearch and Reflection Journal
Research and Reflection Journal for DGL 104 course

# MV (Model View) Architectural Patterns

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
  - One-Way: View pulls data or notifies ViewModel (manual updates).
  - Two-Way: View and ViewModel sync automatically (less boilerplate).
  
- Ideal for real-time data updates.
- Common in modern Android (Jetpack Compose), SwiftUI, and web frameworks (Vue, Angular, React).  

### Summary

MVC (Model-View-Controller) and MVVM (Model-View-ViewModel) are UI architectural patterns that separate concerns in software, with MVC using a Model for data/logic, a passive View for display, and a Controller to handle interactions. while MVVM employs a Model, a View, and a ViewModel that connects them via data binding (one-way or two-way) for automatic updates, reducing code.

## Reference

- Model-View-Controller : https://www.youtube.com/watch?v=DUg2SWWK18I
- Model-View-ViewModel : https://www.youtube.com/watch?v=AXpTeiWtbC8
   - https://www.educative.io/courses/javascript-design-patterns-for-coding-interviews/mvvm-pattern?utm_term=&utm_campaign=%5BNew+-+Mar+24%5D+Brand+Core+Performance+Max&utm_source=adwords&utm_medium=ppc&hsa_acc=5451446008&hsa_cam=21099703438&hsa_grp=&hsa_ad=&hsa_src=x&hsa_tgt=&hsa_kw=&hsa_mt=&hsa_net=adwords&hsa_ver=3&gad_source=2&gclid=EAIaIQobChMIgv_1g5rCjAMVlzatBh38ZSANEAEYASAAEgL8jfD_BwE

- Data Binding: https://www.youtube.com/watch?v=9G9eYCSdJvU

