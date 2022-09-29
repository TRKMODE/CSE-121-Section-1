# Introduction to Turtles

## Table of Content

1. [Introduction](#introduction)
2. [Preliminary Step](#preliminary-step)
3. [Preparing the Turtle Tools](#preparing-the-turtle-tools)
4. [Using the Turtle Tool](#using-the-turtle-tool)

---

## Introduction

Turtles are Objects (tools) that allows us to draw a picture and animate the process of drawing our picture at the same time.

> Using Turtle in Java are similar to using a pen in real life to draw.

---

## Preliminary Step

Some tools in Java are not included when you install Java (JDK). As a result, we need to get this tool separately and add them into our folder that directly contains our Java code.

> Find the code for Turtle.java here: [Click Me!](https://raw.githubusercontent.com/NicholasSeward/Turtle/main/Turtle.java)

Step by step instruction:

1. Create a new file in the folder where you will create / have created your Java program.
2. Go to the link above
3. Copy the whole code
4. Paste the whole code into the new file you just created
5. Save the code as `Turtle.java`

---

## Preparing the Turtle Tools

To use the Turtle tools in our program, we have to create a new Turtle tool in our program and save it to a variable with the following code:

```java
Turtle turtleDrawer = new Turtle();
```

Explanation:

1. The code above follows the template on how to create a variable.
2. `Turtle` is the variable type
3. `turtleDrawer` is the variable name. Feel free to change this if you want!
4. `new Turtle()` is creating a new Turtle Object (tool) that we are saving into our variable.

---

## Using the Turtle Tool

After creating the Turtle Object in our program and saving it to a variable, we can use it with the following template:

```
turtleName.command(...);
```

Explanation:

1. `turtleName` should be replaced with the variable name where we saved our Turtle Object. 

    For example, if we use the code from above:
    ```java
    Turtle turtleDrawer = new Turtle();
    ```

    We will replace `turtleName` with turtleDrawer

2. `command` should be replaced by the name of the command that a Turtle can do. Some of the commmand that we will learn this week are:

    - **_penColor_**: sets the color of the drawing
    - **_forward_**: move the Turtle / pen forward
    - **_left_**: make the Turtle / pen turn left
    - **_right_**: make the Turtle / pen turn right
    - **_up_**: Allows the Turtle / pen to be moved without actually drawing anything
    - **_down_**: Allows the Turtle to draw again (generally used after the **_up_** command)

3. The `...` between the set of parenthesis will be replaced by a number or String dpeending on the command that you use from above (more details here: [Click Me!](/Using%20Turtle.md)).

Example:
```java
Turtle turtleDrawer = new Turtle();

turtleDrawer.penColor("red");

turlteDrawer.forward(100);

```

Output:

![Output](/img/turtle.png)
