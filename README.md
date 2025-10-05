# Template Method Pattern - Order Processing System
Overview

This project demonstrates the Template Method Design Pattern in Java. The pattern defines the skeleton of an algorithm in a superclass while allowing subclasses to override specific steps without changing the overall algorithm structure.

The system simulates order processing for different types of orders using this design pattern.

Project Structure

NetOrder.java – Concrete implementation of a network order.

StoreOrder.java – Concrete implementation of a store order.

OrderProcessTemplate.java – Abstract template class defining the steps of order processing.

TemplateMethodPatternClient.java – Client class to test and demonstrate the template method pattern.

README.md – Project documentation.

Features

Demonstrates code reuse via abstract template methods.

Allows easy extension for new order types without modifying existing logic.

Clear separation of common algorithm steps and specific implementations.

How to Run

Clone the repository:

git clone <repository-url>


Compile all Java files:

javac *.java


Run the client:

java TemplateMethodPatternClient
