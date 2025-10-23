# My Coding Notebook
## Table of contents
- [Flutter Notes](#flutter-notes)
- [What is Flutter?](#what-is-flutter)
- [Key Terms and Definitions](#Key-Terms-and-Definitions)
- [Layout and Design Widgets](#Layout-and-design-widgets)
- [Definitions with Structures](#flutter-definitions)
- [Code Definitions](#code-definitions) 
- [Notebook Style Guide](#Markdown-Style-Guide-for-Coding-Notebooks)

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



## Flutter Definitions with structures

| Term | Definition and Description | Base Structure | Real Life Example | App Example |
|------|----------------------------|----------------|-------------------|-------------|
| main()     | A function that runs when your app starts. It tells Flutter what app to show. | `void main() => runApp(MyApp());` |  |  |
| MaterialApp     | The widget that sets up your whole app’s look and navigation. | `MaterialApp(...)` | Starting a game |  |
| Scaffold     | A widget that gives you the basic layout: background, navigation bar, floating button, etc. | `Scaffold(...)` | templates for this table |  'return Scaffold(  body:Column(mainAxisAlignment:MainAxisAlignment.start,children: [' |
| Column     | A widget that holds and displays your content in a straight line from top to bottom. | `Column(...)` | long division | Column(children: [Text(title,style: const TextStyle(color: Colors.blue, fontWeight: FontWeight.bold),textAlign: TextAlign.center, |
| Row     | A widget that shows things side-by-side. | `Row(...)` | information matching the definition  |  |
| Container     | A box that holds other widgets. You can add color, padding, borders, or size. | `Container(...)` | bulleten board background |  Container(width: 200,height: 200,decoration: BoxDecoration(border: Border.all(color: Colors.blue, width: 5),),child: Image.network('https://placedog.net/640/480?random',fit: BoxFit.cover,),), |
| Text     | A widget to display text on the screen. | `Text('Hello')` | Greeting messages |  |
| Image.network     | A widget to show an image using a link from the internet. | `Image.network('https://...')` | Google images |  |
| ElevatedButton     | A clickable button that floats above content. You choose what happens when it's clicked. | `ElevatedButton(onPressed: ..., child: ...)` | tapping buttons on a device |  |
| onPressed     | The code that gets run when a button is tapped or something happens. | `onPressed: () => doSomething()` | volume button on a phone |  |
| StatelessWidget     | A class that creates widgets that never change. Good for static screens. | `class HomeScreen extends StatelessWidget` | a welcome page or a profile page |  |
| StatefulWidget     | A class for widgets that can change while the app is running. | `class MyWidget extends StatefulWidget` | scrolling or playing a game |  |
| Navigator     | Lets you move from one screen to another using route names. | `Navigator.pushNamed(context, '/about')` | pips(navigating through pages) |  |
| Padding     | Makes space around a widget inside its container. | `Padding(padding: EdgeInsets.all(8.0), child: ...)` | the frame of a picture |  |
| Center     | Aligns content in the center of the screen or container. | `Center(child: ...)` |  |  |
| Wrap     | Automatically puts widgets onto a new line when there's no space. | `Wrap(children: [...])` | writing in a google document |  |
| @override     | This marks a method as one that’s replacing a method in a parent class. | `@override` |  |  |
| Widget Build     | The special function in every widget that describes what gets drawn on the screen. | `Widget build(BuildContext context) {...}` |  | Widget build(BuildContext context) { return MaterialApp( |
| build     | Required in every widget class to describe what to show. | `build` |  |  |
| BuildContext     | A variable that helps the widget know where it is and lets it communicate with the app. | `BuildContext context` | When you go through websites and it lets you see what you have done |  |
| super.key     | A keyword used to pass a value to the parent widget. | `super.key` |  |  |
| const     | A keyword that means the value won't change and is set once. | `const` | the title of a homescreen or page |  |







## Code Definition
| Term | Definition | Base Structure / Syntax | Real Life Example | App Example |
|------|------------|--------------------------|-------------------|-------------|
| Variable | A named container used to store a value that may change. | `var x = 5;` | student ID  | mn.dart, String title: 'TSA Portfolio' , |
| constant | A fixed value that cannot change once set. | `const PI = 3.14;` |  | main.dart, const MyPortfolioApp((super.key)); |
| Data Type | The kind of value a variable holds, like numbers or text. | `int`, `String`, `bool` |  | main.dart, bool, debugShowCheckedModeBanner: false, |
| string | A sequence of characters used to represent words or text. | `"Hello World"` |  |  |
| Interger | Whole number values. | `int age = 16;` |  |  |
| Double | Number values with decimals. | `double age = 16.2;` |  |  |
| Boolean | A value that can be true or false. | `bool isLoggedIn = false;` |  |  |
| List | A collection of values in a specific order. | `List<String> names = [];` |  |  |
| Null| A special value that means “nothing.” | `String? name = null;` |  |  |
| Function| A reusable block of code that performs an action. | `void sayHi() { print("Hi"); }` |  |  |
| Paraeter| The information passed into a function to change how it works. | `greet(String name)` |  |  |
| Return | The result a function gives back. | `return total;` |  |  |
| Scope | Where a variable or function can be used. | (No set syntax — concept-based) | giftcards |  |
|Class| Blueprint for creating objects with specific structure and behavior. | `class Dog {}` | water bottle or computer |  |
|Object| A specific version of a class. | `Dog myDog = Dog();` | blueprint or template |  |
|Property | A variable that belongs to a class/object. | `String name;` |  |  |
| Method| A function that belongs to a class. | `void bark() {}` | Teacher: teach, mentor, instruct |  |
|Constructor | A special function used to set up a class when it’s created. | `Dog(this.name);` | creating a google document and there is a default title |  |
|Abstaction| Hiding the inner workings of code so users only interact with what they need. | (Concept — not specific code) | computers hiding their inner workings |  |
|Override | Changing how a built-in or inherited function behaves. | `@override` |  |  |
|Void| A function that does not return a value. | `void printMessage() {}` |  |  |
| Scanner| Creates a scanner object to take input from user  | Scanner in = new Scanner(System.in); |  |  |
| Import Scanner|  | |  |  |
| print line statement|| |  |  |
| print statement | | |  |  |
| input nextLine | | |  |  |
| input nextInt | | |  |  |
| input nextDouble | | |  |  |
| input nextBoolean | | |  |  |







## Markdown Style Guide for Coding Notebooks

Follow this guide to keep your coding notebook **clear, consistent, and professional**.  
This ensures your notes are easy for you (and others) to read later.

---

## 🔹 Headings
**When to use:** Organize your notebook into sections (like days, topics, or projects).  
- `#` for the notebook title (use once at the top).  
- `##` for each day or major topic.  
- `###` for subsections (like "Notes", "Practice", "Reflections").  

✅ Example:


# My Coding Notebook
## Day 1
### Notes
### Practice

🔡 Text Formatting
When to use: Highlight important ideas or add emphasis.

Use bold for key terms or definitions.

Use italic for emphasis or side comments.

Use inline code for keywords, functions, or commands.

 

✅ Example:

**Class** = a blueprint for objects  
*Remember:* always test your code  
Use `System.out.println()` to print

 

💻 Code Blocks
When to use: Anytime you write multiple lines of code.

Inline code for short snippets.

Fenced code blocks with language for full examples.

✅ Example:

```java
public class Hello {
    public static void main(String[] args) {
        System.out.println("Hello World!");
    }
}
```

🧾 Lists
When to use: Organize steps, notes, or key points.

Numbered lists for sequences or steps.

Bulleted lists for unordered ideas.

✅ Example:

1. Define the class
2. Write the main method
3. Test your program

Variables
- Loops
- Conditionals
 

✅ Checklists
When to use: Track progress on assignments or tasks.

✅ Example:

[x] Complete coding warm-up
- [ ] Finish project draft
- [ ] Reflect on learning

 

➡️ Blockquotes
When to use: Call out notes, reminders, or teacher comments.

✅ Example:

> 💡 Remember: Loops repeat code until a condition is false.

 

📊 Tables
When to use: Compare values, track progress, or organize data neatly.

✅ Example:

| Task        | Status   | Notes          |
|-------------|----------|----------------|
| Homework 1  | Done ✅  | Submitted      |
| Homework 2  | Pending  | Needs review   |

 

🔗 Links & Images
When to use: Add references, resources, or visuals.

✅ Example:

[Java Docs](https://docs.oracle.com/javase/8/docs/api/)  
![Markdown Logo](https://upload.wikimedia.org/wikipedia/commons/4/48/Markdown-mark.svg)

 

📂 Collapsible Sections
When to use: Hide solutions, extended notes, or extra details.

✅ Example:

<details>
  <summary>Click to reveal solution</summary>
  
System.out.println("Answer: 42");

</details>

 

📝 Footnotes
When to use: Add references or side notes without cluttering the page.

✅ Example:

This concept is related to object-oriented programming.[^1]

[^1]: See "Objects and Classes" in your textbook.

 

🎯 Style Rules
Consistency matters more than creativity

Always use headings to structure your notes.

Always use code blocks for multi-line code.

Clarity first

Bold key terms.

Use lists instead of long sentences when outlining steps.

Professional tone

Don’t mix casual notes with formal work in the same section.

Use blockquotes for reflections or teacher feedback.

Track your learning

Use checklists to mark what’s done.

Use collapsible sections if you want to hide answers until review time.

 

✅ Bottom Line:

Headings = Structure

Bold/Italic = Emphasis

Code blocks = Code

Lists = Steps/Ideas

Tables = Organization

Checklists = Progress

Blockquotes = Notes/Tips

Collapsible = Hide/Show detail

Keep it simple, consistent, and clear.
