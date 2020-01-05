### Dependency Injection

1. Intent
    - Dependency injection solves problems such as:
        + How can an application or a class be independent of how its objects are created?
        + How can the way objects are created be specified in separate configuration files?
        + How can an application supports different configurations?
    - Creating an object directly within the class that requires objets is inflexible because it commits the class to particular objects and makes it impossible to change instantiation later independently from (without having to change) the class. It stops the class from being usable when other objects are required, and make it harder to test because real objects can't be replaced by mock objecs.
    - A class is no longer responsible for creating objects it requires.