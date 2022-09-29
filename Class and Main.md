# Introduction to Class and Main Method

## Table of Content

1. [Introduction](#introduction)
2. [Writing a Class](#writing-a-class)
3. [Writing the Main Method](#writing-the-main-method)
4. [Curly Braces in Java](#curly-braces-in-java)
5. [Combining the Class and the Main method](#combining-the-class-and-the-main-method)

---

## Introduction

Before we start writing a Java program, we need to prepare two things first:

1. Class
2. Main Method

To help us understand the role of Class and Main Method, see the diagram below:

![Class and Main Method Diagram](/img/class%20and%20main.png)

From the diagram above, we can make the following observation:
1. A class is similar to a giant box that contains everything inside it, including the main method and our actual code.
2. A main method is a smaller box inside the class that <u>**directly**</u> contains our actual code inside it.

---

## Writing a Class

When writing a Class, there are 4 components that we need to write:

1. The keyword `public`
2. The keyword `class`
3. Your Class name
4. A set of opening and closing curly braces

Example:
```java
public class HelloWorld {

}
```

> It's extremely important to remember that your Class name **MUST** be identical to the file name (case sensitive) with `.java` added at the end of the file name. 
>
> In the example above, the file name must be `HelloWorld.java`

---

## Writing the Main Method

When writing the Main method, it should be identical to the code below:

```java
public static void main(String[] args) {

}
```

---

## Curly Braces in Java

Notice that when we write our Class and Main method, we have a set of opening and closing curly braces. They work as follow:

1. The opening curly braces `{` indicates the start of the structure we are writing.
2. The closing curly braces `}` indicates the end of the structure we are writing.
3. Anything between the two curly braces indicates content inside the structure we are writing.

Example:
```
public class HelloWorld { <-- start of the HelloWorld class

    --> this is inside the Hello World Class <--

} --> end of the HelloWorld class
```

---

## Combining the Class and the Main method

To tie everything together, we need to go back to our diagram at the very top in order to understand how the structure should be ordered. 

Following our diagram, our code now looks like below:
```java
public class HelloWorld { --> start of HelloWorld class
    
    public static void main(String[] args) { --> start of main method

        --> Your Code Inside Here <--

    } <-- end of main method

} <-- end of HelloWorld class
```

> Notice that the main method and all of its content is between the opening and closing curly braces for our HelloWorld class. This represents our diagram that the main method and all of its content should be inside the class.

> Note: The arrows are not part of the syntax.
