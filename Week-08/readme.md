[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/MMj2nZMu)
# Resarch and Reflection Journal
Research and Reflection Journal for DGL 104 course

# Functional Requirements & User Stories

## Introduction
This lecture covers **Functional requirements** and **User stories**, essential tools in software development. It emphasizes the importance of analyzing apps not just from a user experience perspective but also from a technical standpoint. As developers, understanding how apps function under the hood is crucial.

## Understanding User Stories
User stories are a common tool for defining user-facing systems. They are typically structured as:

User stories are written in natural language and aim to capture user interactions within an application. They serve as a great tool for communication within development teams, ensuring a shared understanding of the app's intended functionality.

### Advantages of User Stories:
- Improve communication and ensure team alignment.
- Are easy to understand by both technical and non-technical stakeholders.
- Provide clear guidance for feature development.

### Disadvantages of User Stories:
- Lack technical implementation details.
- May overlook non-functional requirements like performance and security.
- Require additional documents to define technical specifics.

## Technical Design Document (TDD)
A **Technical Design Document (TDD)** addresses the technical aspects of an application, bridging the gap between user stories and implementation.

### Contents of a TDD:
- **Architectural details** (e.g., MVC architecture for mobile apps).
- **Implementation details** for complex or untested features.
- **Testing plans** to ensure software functionality.
- **Performance criteria** (e.g., speed, scalability, memory usage).

TDDs are particularly useful in the early stages of development but may become outdated once the actual implementation begins.

## Functional Requirements
Functional requirements define software features in terms of **input and output**. They describe what a system should do, often derived from user stories and use cases.

# Week-08: Research a New Language

## Processing

**Processing** is an open-source programming language and development environment built on Java, designed to make coding accessible for creative applications. It enables users to quickly "sketch" interactive visuals, animations, and data visualizations with a simplified syntax and a rich set of graphics libraries. 

- Example: "Processing is used to create interactive visuals, animations, and data visualizations for creative projects."
- 
# Interactive Color Changing Circle

```java
color bgColor;
color circleColor;

void setup() {
  size(600, 400);
  bgColor = color(255);
  circleColor = color(0, 0, 255);
}

void draw() {
  background(bgColor);
  fill(circleColor);
  ellipse(width/2, height/2, 100, 100);
}

void mousePressed() {
  bgColor = color(random(255), random(255), random(255));
  circleColor = color(random(255), random(255), random(255));
}
```
### Overview:
- Originally developed at **MIT in 2001** by **Casey Reas and Ben Fry**.
- Intended as a tool for **non-programmers**, especially artists and designers, to learn programming basics while creating compelling visual art.

### Why These Resources?
- The **tutorials and examples** provide immediate visual feedback, essential for understanding programming in a visual context.
- **Processing’s design philosophy** emphasizes rapid prototyping, encouraging learners to experiment.
- 
The following example demonstrates how Processing's tutorials and examples offer immediate visual feedback and encourage rapid prototyping.

```java
color bgColor;

void setup() {
  size(600, 400);
  bgColor = color(200);
}

void draw() {
  background(bgColor);
  fill(0);
  textSize(32);
  text("Press any key to change color", 50, height/2);
}

void keyPressed() {
  // Immediate visual feedback: change to a random background color
  bgColor = color(random(255), random(255), random(255));
}
```
## User Story: Spotify

### 1. Create a New Playlist
**As a user, I can click on a “New Playlist” button to create a new playlist so that I can start organizing my songs.**
- A visible **“New Playlist”** button exists on the home or library screen.
- Clicking the button opens a prompt to enter a **playlist name**.
- The newly created playlist appears immediately in the **user’s playlist list**.

### 2. Add Songs to an Existing Playlist
**As a user, I can add songs to an existing playlist so that I can build my personalized music collection.**
- Each song has an **options menu** with an **“Add to Playlist”** option.
- The user can choose from a **list of existing playlists** when adding a song.

### 3. Reorder Songs
**As a user, I can reorder songs by dragging and dropping them so that I can customize the playback order.**
- Songs display a **drag handle** or similar indicator.
- **Drag-and-drop** functionality allows reordering without error.

### 4. Edit Playlist Name & Description
**As a user, I can edit the playlist’s name and description so that the playlist reflects its theme or mood.**
- An **“Edit”** option is available on the playlist’s **details page**.
- Fields for the **playlist name and description** are editable.

### 5. Share a Playlist
**As a user, I can share my playlist via a shareable link or social media so that my friends can enjoy my curated music.**
- A **“Share”** button is visible on the **playlist details page**.
- Options include **social media sharing** and a **copyable link**.
- The shared playlist link directs recipients to the **correct playlist**.

### Reflection
Processing is an excellent language for visual programming, and user stories like the ones above help define software functionality clearly. The structured approach ensures a seamless user experience for platforms like Spotify.

# References

- **Functional Requirements & User Stories:**  
  - [User Stories Applied: For Agile Software Development by Mike Cohn](https://www.amazon.com/dp/0321205685/)  
  - [Writing Effective Use Cases by Alistair Cockburn](https://www.amazon.com/dp/0702121020/)

- **Technical Design Document (TDD):**  
  - [IEEE Std 830-1998: IEEE Recommended Practice for Software Requirements Specifications](https://ieeexplore.ieee.org/document/730688)  
  - [Software Requirements by Karl Wiegers](https://www.amazon.com/dp/0735679665)

- **Processing (Programming Language):**  
  - [Official Processing Website](https://processing.org/)  
  - [Getting Started with Processing by Casey Reas and Ben Fry](https://www.amazon.com/dp/0981389016)

