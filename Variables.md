# Variables

## Table of Content

1. [Introduction](#introduction)
2. [Primitives](#primitives)
3. [Object](#object)
4. [Creating a Variable](#creating-a-variable)
5. [Variables and Printing](#variables-and-printing)

---

## Introduction

Variables are "boxes" that stores two possible things:

1. Simple information called _primitives_
2. More complex information / Tools called _Object_

> Variables must be inside the Class. However, it may be declared inside or outside of the main method.
>
> For the purpose of this class, variables should be declared inside the main method unless told otherwise.

---

## Primitives

Primitives are simple information that includes but limited to:

1. Whole number (formally called `int` which stands for integer)
2. Decimal number (formally called `double`)
3. true or false (formally called `boolean`)
4. Single character (formally called `char`)

Examples (in order):
```
1285
5.7
false
'z'
```

---

## Object

> This will become more clear and relevant in [Introduction to Turtle](/Turtle%20Introduction.md).

Object are more complex information or tools that can be used to perform specific task in our program.

An example of Object that we have learned is String. We will dive deeper into why String is an Object in Java in future CS classes :)

More examples of Object that we will learn in the following weeks:

- `Scanner`, a tool that allows us to read text from different sources
- `PrintStream`, a tool that allows us to print text to different destinations
- `Turtle`, a tool that allows us to draw and animate the process of our drawing

> Notice that the name of Object always start with a capital letter (unlike primitive). This is also true for `String`!

---

## Creating a Variable

To create a variable, we must follow the template below:

```
type variableName = information;
```

Example:
```java
int bunchaNumbers = 1375;
```

```java
char someLetter = 'z';
```

```java
String someText = "I like turtles"
```

Explanation:

1. `int`, `char`, `String` are the variable type. This must align with the information that we are planning to store into the variable.
2. `bunchaNumbers`, `someLetter`, `someText` are variable names. These are mostly up to us (though certain formal and informal rules apply).
3. `1375`, `'z'`, `"I like turtles"` are the information that we want to store
into our variables. This must align with the variable type.

---

## Variables and Printing

One small application that we can now apply is combining variables and printing. Instead of printing a text directly, we can now store our text into a variable before printing it. 

Example:

```java
String someText = "hello";
System.out.println(someText);
```

Output:
```
hello

```

Notice the absence of an opening and closing double quotation our our `System.out.println(...)` code. We do not use double quotation in this case because we want Java to treat `someText` as a reference to a variable (not a text).

Compare the example above with the code below:

```java
String someText = "hello";
System.out.println("someText");
```

Output
```
someText

```

The code right above tells Java to treat `someText` on line 2 as a text instead of a reference to the variable we declared above it because of the double quotation mark on line 2.
