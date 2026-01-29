# Code Refactoring
# Video Store Code Refactoring Project

## Project Overview
This repository contains a **Java** implementation of the classic **Video Store Refactoring Kata**. The primary goal of this project is to demonstrate **Code Refactoring** techniques to transform legacy procedural code into a modern, **Object-Oriented** design.

By analyzing the source code, you can see practical examples of how to identify and fix common **Bad Smells** to produce **Clean Code**.

## Key Refactoring Techniques Used
This project demonstrates the following **Refactoring** techniques:
* **Replacing Switch Statements with Polymorphism:** Converting complex `switch` logic in `Movie.java` into a flexible class hierarchy (`RegularPrice`, `NewReleasePrice`, `ChildrensPrice`).
* **State Pattern:** Implementing the **State Design Pattern** to handle pricing logic dynamically.
* **Extract Method:** Breaking down **Long Methods** in `Customer.java` to improve readability.
* **Move Method:** Solving **Feature Envy** by moving logic from the `Customer` class to the `Rental` class.

## Search Tags
Refactoring, Java, Clean Code, Design Patterns, Code Smells, Martin Fowler, Refactoring Kata, OOP, Software Engineering, Legacy Code, State Pattern, Polymorphism.
