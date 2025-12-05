PROJECT TITLE: Queue Simulator using Java
PURPOSE OF PROJECT: Learning Java
VERSION or DATE: 20th April 2024
HOW TO START THIS PROJECT:
AUTHORS: Arash Heidarzadeh Naeini

Grocery Queue Simulator

This project is a simple console-based Grocery Queue Simulator written in Java. It demonstrates how a queue data structure works by allowing users to add customers, remove them in order, view the next customer, check size, and verify if the queue is empty or full. It uses Java’s built-in `LinkedList` implementation of `Queue` to manage customer flow efficiently. :contentReference[oaicite:2]{index=2}

Features

- Enqueue Customers – Add a customer to the end of the queue  
- Dequeue Customers – Remove the customer at the front  
- Peek – View the first customer without removing them  
- Check Empty – See if the queue has no customers  
- Check Full – Always false, as LinkedList has no capacity limit  
- Queue Size – Displays the current number of customers  
- Menu-Driven Interaction – User chooses actions through numbered options  
- Loop Control – Continue or exit based on user input  

How It Works

The simulator runs inside a loop, displaying a menu and asking the user to select an operation. Each function interacts with the queue using built-in Java methods like `add()`, `remove()`, `peek()`, `isEmpty()`, and `size()`. Because `LinkedList` is dynamically sized, the queue never becomes “full.” :contentReference[oaicite:3]{index=3}

Technologies Used

- Java
- Queue Interface
- LinkedList Collection
- Scanner for User Input

Running the Program

1. Compile the file:
   ```bash
   javac GroceryQueueSimulator.java
