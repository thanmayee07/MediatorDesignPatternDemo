# MediatorPatternDemo

The Mediator design pattern is a behavioral pattern that promotes loose coupling among objects by centralizing their communication. In this pattern, instead of objects directly interacting with each other, they communicate through a central mediator. This mediator encapsulates the interactions between objects and helps reduce dependencies between them.
Key Components
Mediator: The central component that facilitates communication between objects. It maintains references to all objects that need to interact and defines methods to coordinate their communication.

Colleague Objects: These are the objects that interact with each other through the mediator. Colleague objects are unaware of each other and rely on the mediator to relay messages.
