# My Coding Notebook

## Table of Contents
-[Flutter Notes](#flutter-notes)
  - [What Is Flutter?](#what-is-flutter)
  - [Key Terms And Definitions](#key-term-and-definitions)
  - [Layout and Design Widgets] (#layout-and-design-widgets) 
  - [Flutter Definitions With Structures](#flutter-definitions-with-structures)
- [Code Definitions](#code-definitions)
- [Notebook Style Guide](#markdown-style-guide-for-coding-notebook)








## Flutter Definitions With Structures

| Term | Definition and Description | Base Structure | Real Life Example | App Example |

|------|----------------------------|----------------|-------------------|-------------|
| main()  | A function that runs when your app starts. It tells Flutter what app to show. | `void main() => runApp(MyApp());` |  | in main.dart, void main() => runApp(MyPortfolioApp()); |
| MaterialApp | The widget that sets up your whole app’s look and navigation. | `MaterialApp(...)` |  | return MaterialApp( debugShowCheckedModeBanner: false, title: 'TSA Portfolio', theme: ThemeData( , and more |
| Scaffold | A widget that gives you the basic layout: background, navigation bar, floating button, etc. | `Scaffold(...)` |  | in home.dart return Scaffold(, body: Padding( |
| Collums | A widget that holds and displays your content in a straight line from top to bottom. | `Column(...)` |  | child: Column(, mainAxisAlignment:, MainAxisAlignment.center, children: [ |
| Rows  | A widget that shows things side-by-side. | `Row(...)` |  |  |
|  Container  | A box that holds other widgets. You can add color, padding, borders, or size. | `Container(...)` |  |  |
|  Text  | A widget to display text on the screen. | `Text('Hello')` |  |  |
|  Image.network  | A widget to show an image using a link from the internet. | `Image.network('https://...')` |  |  |
|  ElevatedButton  | A clickable button that floats above content. You choose what happens when it's clicked. | `ElevatedButton(onPressed: ..., child: ...)` |  |  |
|  onPressed  | The code that gets run when a button is tapped or something happens. | `onPressed: () => doSomething()` |  |  |
|  StatelessWidget  | A class that creates widgets that never change. Good for static screens. | `class HomeScreen extends StatelessWidget` | Logo |  |
|  StatefulWidget  | A class for widgets that can change while the app is running. | `class MyWidget extends StatefulWidget` |  |  |
|  Navigator  | Lets you move from one screen to another using route names. | `Navigator.pushNamed(context, '/about')` |  |  |
|  Padding  | Makes space around a widget inside its container. | `Padding(padding: EdgeInsets.all(8.0), child: ...)` |  |  |
|  Center  | Aligns content in the center of the screen or container. | `Center(child: ...)` |  |  |
|  Wrap  | Automatically puts widgets onto a new line when there's no space. | `Wrap(children: [...])` |  |  |
|  Override  | This marks a method as one that’s replacing a method in a parent class. | `@override` |  |  |
|    | The special function in every widget that describes what gets drawn on the screen. | `Widget build(BuildContext context) {...}` |  |  |
|  build()  | Required in every widget class to describe what to show. | `build` |  |  |
|  BuildContext  | A variable that helps the widget know where it is and lets it communicate with the app. | `BuildContext context` |  |  |
|  super.key  | A keyword used to pass a value to the parent widget. | `super.key` |  |  |
|  const  | A keyword that means the value won't change and is set once. | `const` |  |  |



## Code Definitions

| Term | Definition | Base Structure / Syntax | Real Life Example | App Example |

|------|------------|--------------------------|-------------------|-------------|

|  Variable  | A named container used to store a value that may change. | `var x = 5;` | Score | main.dart title: 'TSA Portfolio', |
|  Constant  | A fixed value that cannot change once set. | `const PI = 3.14;` |  | main.dart, const MyPortfolioApp({super.key}); |
|  Data Type  | The kind of value a variable holds, like numbers or text. | `int`, `String`, `bool` | Wearing a 3XL when your a S | main.dart, bool, debugShowCheckedModeBanner: false, |
|  String  | A sequence of characters used to represent words or text. | `"Hello World"` |  | 'HI EVERYONE,\nWelcome to the',
|  Integer  | Whole number values. | `int age = 16;` |  | fontSize: 28, |
|  Double  | Number values with decimals. | `double age = 16.2;` |  | padding: EdgeInsets.all(8.0), |
|  Boolean  | A value that can be true or false. | `bool isLoggedIn = false;` |  |  |
|  List  | A collection of values in a specific order. | `List<String> names = [];` |  | final List<String> puppyUrls = [ |
|  Null  | A special value that means “nothing.” | `String? name = null;` |  |  |
|  Function  | A reusable block of code that performs an action. | `void sayHi() { print("Hi"); }` | Clicking a next button to go to the next page |  |
|  Parameter  | The information passed into a function to change how it works. | `greet(String name)` |  |  |
|  Return  | The result a function gives back. | `return total;` |  |  |
|  Scope  | Where a variable or function can be used. | (No set syntax — concept-based) |  |  |
|  Class  | Blueprint for creating objects with specific structure and behavior. | `class Dog {}` |  |  |
|  Object  | A specific version of a class. | `Dog myDog = Dog();` |  |  |
|  Property  | A variable that belongs to a class/object. | `String name;` | Waterbottles |  |
|  Method  | A function that belongs to a class. | `void bark() {}` | Completing an assignment |  |
|  Constructor  | A special function used to set up a class when it’s created. | `Dog(this.name);` |  |  |
|  Abstraction  | Hiding the inner workings of code so users only interact with what they need. | (Concept — not specific code) |  |  |
|  Override  | Changing how a built-in or inherited function behaves. | `@override` |  |  |
|  Void  | A function that does not return a value. | `void printMessage() {}` |  |  |

| Scanner | Creates a scanner onject to take input from user | Scanner in = new Scanner(System.in); |  |  |
| import Scanner | Gives access to Scanner class, required at top | import java.util.Scanner); |  |  |
| print statement | prints the content in the parenthesis, adds line after | System.out.println(" "); |  |  |
| input nextLine | Reads in a string from the user | input.nextLine(); |  |  |
| input nextInt | Reads in a int from the user | input.nextInt(); |  |  |
| input nextDouble | Reads in a double (decimal) from the user | input.nextDouble(); |  |  |
| input nextBoolean | Reads in a boolean (true/false) from the user | input nextBoolean(); |  |  |
 | Arithmetic operators |   -      *      /     % (modulus, returns the remainder from dividing) |  |  |  |
 | Compound operators (applies the result to the variable) | +=      -=     *=    /=     %=    ++ (adds 1) |  |   |   |





