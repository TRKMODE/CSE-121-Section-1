# Printing

## Table of Content

1. [Introduction](#introduction)
2. [Text in Java](#text-in-java)
3. [System.out.println(...)](#systemoutprintln)
4. [System.out.print(...)](#systemoutprint)
5. [More Examples](#more-examples)
---

## Introduction

The first code that we will learn to write is regarding printing text into the console.

> The console is a special place where the output produced by your program and/or any error message is displayed.

---

## Text in Java

Text in Java (generally called _String_) are 0 or more letter surrounded by an opening and closing double quotation mark.

Example:
```
"hello"  -> a valid String
'hello'  -> not a valid String
hello    -> not a valid String
```

---

## `System.out.println(...)`

The code `System.out.println(...)` does two things:

1. Prints the String between the set of parenthesis
2. Moves the output to a new line **AFTER** the String is printed

Example:
```java
System.out.println("hello");
System.out.println("hi");
```

Output:
```
hello
hi

```

Explanation:
- `System.out.println("hello");` prints the text `hello` and moves the output to to the next line **PRIOR** to printing `hi`
- `System.out.println("hi");` prints the text `hi` and moves the output to the next line. Since there are no more text to be printed, this creates a blank line.

---

## `System.out.print(...)`

The code `System.out.print(...)` prints out the String between the set of parenthesis <u>**WITHOUT**</u> moving the output to a new line afterwards.

Example:
```java
System.out.print("hello");
System.out.print("hi");
```

Output:
```
hellohi
```

> Notice the absence of the extra blank line at the very end.

---

## More Examples

Below are the example of combining `System.out.println()` and `System.out.print()`:

```java
System.out.println("hello");
System.out.print("hi");
System.out.print("huh");
System.out.println("how?");
System.out.print("hey...");
```

Output:
```
hello
hihuhhow?
hey...
```