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
