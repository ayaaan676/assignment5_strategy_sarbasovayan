# Assignment 5 — Strategy Pattern

## Student Information
- Student: Ayan Sarbasov
- Group: SE2538
- Course: Software Design Patterns

## Project Overview

This project demonstrates the Strategy design pattern using a simple calculator.

The calculator supports three operations: addition, subtraction, and multiplication. Each operation is implemented as a separate strategy.

## Project Structure

- `Strategy.java` — common strategy interface.
- `AddStrategy.java` — addition algorithm.
- `SubtractStrategy.java` — subtraction algorithm.
- `MultiplyStrategy.java` — multiplication algorithm.
- `Calculator.java` — context that executes the selected strategy.
- `Main.java` — demonstrates the application.

## How to Run

1. Open the project in IntelliJ IDEA.
2. Make sure JDK 17 is configured.
3. Open `Main.java`.
4. Run the `main` method.

## How to Add a New Strategy

Create a new class that implements the `Strategy` interface and overrides the `execute()` method. Then pass an instance of this class to the calculator using `setStrategy()`.

Existing strategy classes do not need to be modified.

## Conclusion

The Strategy pattern makes the calculator flexible and easy to extend. New operations can be added without changing the existing calculator logic.