## Intro to Software Architecture

Software architecture is the foundation of any software system and involves making design decisions that will impact the system's functionality, performance, and maintainability.

- [Software Architecture Guide](https://martinfowler.com/architecture/) by Martin Fowler, Chief Scientist, ThoughtWorks
    - Martin covers:
        - What is software architecture?
        - Why does it matter?
        - Application architecture
        - Enterprise architecture

## How to Think About Architecting Software

Effective software architecture requires a holistic approach that considers the system's context, stakeholders, requirements, and constraints. It involves identifying and prioritizing architectural drivers, creating architectural views, and communicating the architecture to stakeholders.

- [Don’t Let Architecture Astronauts Scare You](https://www.joelonsoftware.com/2001/04/21/dont-let-architecture-astronauts-scare-you/) by Joel Spolsky, CEO, Stack Overflow
    - Joel emphasizes the importance of solving useful problems, rather than fixating on interesting architectures.

## Software Design Patterns

Software design patterns are reusable solutions to common software design problems. They provide a vocabulary for discussing design decisions and can help architects make informed choices about the system's structure and behavior.

- [Design Patterns](https://refactoring.guru/design-patterns) by Alexander Shvets, Founder, Refactoring.Guru
    - Alexander covers:
        - What's a design pattern?
        - Benefits of design patterns
        - Catalog of 22 patterns
        - History of patterns
        - Criticism of patterns
- [The SOLID Principles of Object-Oriented Programming Explained in Plain English](https://www.freecodecamp.org/news/solid-principles-explained-in-plain-english/) by Yigit Kemal Erinc, Software Engineer, numi solutions
    - Yigit provides a well-written breakdown of the SOLID principles:
        - The Single Responsibility Principle
        - The Open-Closed Principle
        - The Liskov Substitution Principle
        - The Interface Segregation Principle
        - The Dependency Inversion Principle

## Architecting Systems for Scale

Architecting systems for scale involves designing systems that can handle increasing amounts of data, users, and traffic. This requires considering factors such as performance, scalability, availability, and fault tolerance.

- [Introduction to architecting systems for scale](https://lethain.com/introduction-to-architecting-systems-for-scale/) by Will Larson, CTO, Carta
    - Will documents some of the scalability architecture lessons he's learned while working on systems at Yahoo! and Digg, around load balancing, caching, off-line processing, and a platform layer.
- [On Designing and Deploying Internet-Scale Services](https://s3.amazonaws.com/systemsandpapers/papers/hamilton.pdf) by James Hamilton, VP & Distinguished Engineer, Amazon Web Services (AWS)

## Software Architecture Principles

Software architecture principles provide guidelines for designing software systems that are flexible, modular, maintainable, and scalable. These principles include separation of concerns, loose coupling, high cohesion, and modularity.

- [Meetup Architecture Principles](https://medium.com/making-meetup/meetup-architecture-principles-dfbe95887c3) by Lara Hogan, VP, Engineering, Kickstarter
    - A VP of engineering describes Meetup's process of identifying their architecture principles: build for change, build for understanding, and build Meetup.

## Software Architecture Examples

Software architecture examples demonstrate how software architecture principles and patterns can be applied in practice. Examples include the layered architecture pattern, the [Microservices](/skill/microservices) architecture pattern, and the event-driven architecture pattern.

- [Exploring Workday’s Architecture](https://medium.com/workday-engineering/exploring-workdays-architecture-73c5dbbffc35) by James Pasley, (Fellow) Software Development Engineer, Workday
    - James provides a big picture overview of Workday's architecture, and then digs into categories of detail including:
        - User Interface Services
        - Metadata-Driven Development
        - The Object Management Services
        - Integration Services
        - Persistence
        - [Analytics](/skill/analytics)
        - Deploying Workday
        - Operations
