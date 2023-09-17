# Mediator-Design-Pattern

The Mediator design pattern is a behavioural pattern that promotes loose coupling among objects by centralizing their communication. In this pattern, instead of objects directly interacting with each other, they communicate through a central mediator. This mediator encapsulates the interactions between objects and helps reduce dependencies between them.

# Key Components
Mediator: The central component that facilitates communication between objects. It references all objects that need to interact and defines methods to coordinate their communication.\
Colleague Objects: These objects interact with each other through the mediator. Colleague objects are unaware of each other and rely on the mediator to relay messages.

BENEFITS OF MEDIATOR PATTERN
1. Decouples Components
2. Promotes Reusability
3. Centralized Control
4. Enhances Maintainability

The Mediator design pattern finds practical applications in solving real-world problems, one of which is the Order Processing system. The aim is to build a basic order processing system where customers can place orders, and order processors communicate through a central mediator to fulfil these orders.

# Overview and Approach
This project demonstrates the Mediator design pattern to manage customer orders and order processors efficiently. It streamlines order placement and centralizes communication.

Approach:
- Customers initiate orders.
- A centralized mediator manages communication.
- Orders are routed to the appropriate processor.
- Real-time order status updates are provided.
- Error handling ensures robustness.


# Environment
The project builds and runs with Visual Studio Community 2022.
