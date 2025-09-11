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




| Term | Definition | Base Structure / Syntax | Real Life Example | App Example |

|------|------------|--------------------------|-------------------|-------------|

|      | A named container used to store a value that may change. | `var x = 5;` |  |  |

|      | A fixed value that cannot change once set. | `const PI = 3.14;` |  |  |

|      | The kind of value a variable holds, like numbers or text. | `int`, `String`, `bool` |  |  |

|      | A sequence of characters used to represent words or text. | `"Hello World"` |  |  |

|      | Whole number values. | `int age = 16;` |  |  |

|      | Number values with decimals. | `double age = 16.2;` |  |  |

|      | A value that can be true or false. | `bool isLoggedIn = false;` |  |  |

|      | A collection of values in a specific order. | `List<String> names = [];` |  |  |

|      | A special value that means “nothing.” | `String? name = null;` |  |  |

|      | A reusable block of code that performs an action. | `void sayHi() { print("Hi"); }` |  |  |

|      | The information passed into a function to change how it works. | `greet(String name)` |  |  |

|      | The result a function gives back. | `return total;` |  |  |

|      | Where a variable or function can be used. | (No set syntax — concept-based) |  |  |

|      | Blueprint for creating objects with specific structure and behavior. | `class Dog {}` |  |  |

|      | A specific version of a class. | `Dog myDog = Dog();` |  |  |

|      | A variable that belongs to a class/object. | `String name;` |  |  |

|      | A function that belongs to a class. | `void bark() {}` |  |  |

|      | A special function used to set up a class when it’s created. | `Dog(this.name);` |  |  |

|      | Hiding the inner workings of code so users only interact with what they need. | (Concept — not specific code) |  |  |

|      | Changing how a built-in or inherited function behaves. | `@override` |  |  |

|      | A function that does not return a value. | `void printMessage() {}` |  |  |
