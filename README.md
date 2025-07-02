🛒 Java E-commerce System
This is a Java-based console and GUI application simulating a basic E-commerce system, where users can browse products, add them to a shopping cart, and place an order. It demonstrates core object-oriented programming (OOP) principles like inheritance, encapsulation, and polymorphism.

📦 Features
Three types of products:

📱 ElectronicProduct: Includes brand and warranty period

👕 ClothingProduct: Includes size and fabric

📚 BookProduct: Includes author and publisher

A Customer can:

Input their name, ID, and address

Choose the number of products to add

Select from the three predefined products

A Cart class to:

Add products

Remove products

Calculate total price

Order class that:

Prints order summary to the console and GUI using JOptionPane

💻 Technologies Used
Java

Java Swing (JOptionPane) for GUI

Scanner for CLI input

🔄 How It Works
The program greets the user and collects their information.

It offers a menu to choose products to add to the cart.

The cart calculates the total.

The user confirms whether to place the order.

The order summary is displayed in both console and GUI.

🧱 Project Structure
Product (Base class)

ElectronicProduct

ClothingProduct

BookProduct

Customer: Stores customer details

Cart: Stores selected products and handles total price & order placement

Order: Finalizes the order and prints a summary

EcommerceSystem: Main class with main() method

🧪 Example
bash
Copy code
Welcome to E-commerce system!
Please enter your id: 101
Please enter your name: Malak
Please enter your address: Alex
How many products you want to add to your cart? 2
Which product you want to add? 
1-smartphone 
2-T-shirt 
3-OOP
➡️ GUI version shows dialog boxes for inputs and product selections.

🚀 Getting Started
Run from Terminal
Compile and run the program:
javac EcommerceSystem.java
java EcommerceSystem

Run with GUI
Uncomment the JOptionPane sections in EcommerceSystem.java to switch to GUI-based flow.

🧠 Concepts Demonstrated
OOP in Java (inheritance, abstraction, encapsulation)

GUI integration using JOptionPane

Input/output using Scanner and System.out
