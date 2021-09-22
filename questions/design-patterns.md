# Design Patterns

## Most Popular Design Patterns

1. Observer Pattern (Passive Observer Pattern)
   - One to many - If one object is modified, dependents are notified
   - https://www.tutorialspoint.com/design_pattern/observer_pattern.htm
2. Decorator Pattern - augmenting code at runtime using procedural methods rather than class based inheritance
3. Factory Pattern - allow classes to be built on "demand" via a factory method call that houses all the abstract and custom logic.
4. Singleton Pattern - one instance of a class/object at run time - running a setup method should only happen one time
5. Command Pattern
6. Adapter Pattern - translate an older piece of code with a translator or adapter class to work with newer incompatible code
7. Facade Pattern - make a difficult API easier to work with via convenience methods (e.g. JQuery makes using the DOM easy)
8. Template Pattern
9. Iterator Pattern - a way to work with data and iterate on it via "next" and "previous" calls - keeping the logic in one single area rather than across files
10. Composite Pattern
11. State Pattern
12. Proxy Pattern - handle a method call through a proxy method, (e.g. if has access, method executes otherwise proxy method interferes)
13. Compound Pattern
14. Bridge Pattern
15. Flyweight Pattern
16. Strategy Pattern - choose the best algorithm at runtime for an input (e.g. MVC chooses the appropriate controller for handling a request)
17. Mediator Pattern - a mediator handles all communication in a program (other program components work with the mediator).

## Context

More patterns in the book, [Design Patterns Elements of Reusable Object-Oriented Software](https://www.google.com/books/edition/Design_Patterns/6oHuKQe3TjQC?hl=en&gbpv=1&printsec=frontcover)

You can also check out Vijay's repo via: https://github.com/vijayxtreme/demo_d_patterns for code samples.

## Questions

- Inheritance vs Composition? Give an example - e.g. React
  - Favor composition over inheritance - React
- Explain the idea of Inversion of Control
  - What is Inversion of Control? [Dylan's Talk](https://www.
    youtube.com/watch?v=L-T0mW1K24Q)
- Write code samples to explain the patterns mentioned above.
- Why should we code towards interfaces and not implementations? What does that even mean? (Hint: Common catchphrase you'll hear at conferences).
  - Why do you think TypeScript can help with JavaScript in terms of following this catchphrase?
