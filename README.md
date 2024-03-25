# Online Shopping System

This project implements an online shopping system consisting of a console-based management interface for the manager and a graphical user interface (GUI) for the client. The system allows the manager to add, delete, print, and save products, while the client can view and add products to the shopping cart through the GUI.

## Phase 1: Design and Class Implementation

UML Diagrams
Use Case Diagram: Represents the interactions between users and the system.
Class Diagram: Illustrates the structure of the system including classes and their relationships.
Class Structure
Product (Abstract Class): Represents a generic product with attributes like ID, name, availability, and price.
Subclasses:
Electronics: Specific information for electronic products such as brand and warranty period.
Clothing: Specific information for clothing products such as size and color.
User: Represents a user account with username and password.
ShoppingCart: Represents the user's shopping cart with methods to manage products.
WestminsterShoppingManager: Implements the ShoppingManager interface to manage products in the system.

## Phase 2: Console Menu Implementation
Menu Options:
Add a new product
Delete a product
Print list of products
Save products to a file

## Phase 3: Graphical User Interface (GUI) Implementation
Features:
Dropdown menu to select product type
Table to display product information
Ability to add products to shopping cart
Display of product details and final price in shopping cart
Discounts applied based on purchase history

## Phase 4: Testing and System Validation
Test Plan:
Define specific scenarios and conditions for testing.
Automated Testing:
Implement unit tests using JUnit or other tools.
Robustness and Quality:
Evaluate error handling, input validation, and adherence to coding standards.

## Instructions for Running the Program
Clone the repository to your local machine.
Compile and run the Java files.
Follow the on-screen prompts for both the console-based management interface and the GUI.

## Requirements
Java Development Kit (JDK)
IDE or text editor for coding (e.g., IntelliJ IDEA, Eclipse)
JavaSwing (for GUI implementation)
