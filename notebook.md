# My Coding Notebook
## Table of contents
- [Flutter Notes](#flutter-notes)
- [What is Flutter?](#what-is-flutter)
- [Key Terms and Definitions](#Key-Terms-and-Definitions)
- [Code Definitions](#code_definitions)
-[Notebook Style Guide](#Markdown-Style-Guide-for-Coding-Notebooks)

## Flutter Notes

### What is Flutter?
- Definition: A framework made by Google for building apps that work on web, Android, and IOS -- with one codebase.
- Why is it useful?
Uses the Dart programming language.
---

### Key Terms and Definitions

| Term             | Definition                                      | Example / Notes                          |
|------------------|--------------------------------------------------|-------------------------------------------|
| Widget           |   Basic building block of a Flutter App. Everything is a widget.           |  Text, Image, Container, Column                         |
| MaterialApp      |   The root of the app. Sets up routes and themes                           |   Found in main.dart                                    |
| Scaffold         |   Provides basic visual layout -- like a header, body, floating button     |   each screen uses it                                   |
| StatelessWidget  |   A widget that doesn't change                                             |   most of the screen flies                              |
| StatefulWidget   |   A widget that can change over time                                       |   Used in MyHomePage()                                  |
| Navigator        |   Manages screen transitions                                               |   Navigator,pushNamed(context, '/page2' );              |
| AppBar           |   Top navigation bar                                                       |   Title of each page appears here                       |
| Column           |   vertical layout                                                          |                                                         |
| Row              |   horizontal layout                                                        |                                                         |
| Container        |   wraps content with padding , margin, or color                            |                                                         |
| Text             |   displays text                                                            |                                                         |
| Image.network    |   displays images from a URL                                               |                                                         |
| Padding          |   adds space around a widget.                                              |                                                         |
| Center           |   centers its child                                                        |                                                         |
| main()           |   the function that runs the app                                           |   found in main.dart                                    |
| Named Routes     |   predefined paths to navigate between screens                             |   '/', '/page2','/page3',etc                            |

---

### Layout and Design Widgets
- How do you center a widget?
- How do you align something to the left or right?
- What widget adds space around content?
