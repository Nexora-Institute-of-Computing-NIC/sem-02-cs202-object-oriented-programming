# CS202 — Object-Oriented Programming — PLAN

**Semester:** 2 · **Credits:** 4 · **Level:** Beginner-Intermediate
**Theory:** 45 hrs · **Lab:** 30 hrs · **Language:** Java

## Syllabus

### Unit 1 — From Procedural to Object-Oriented (9 lectures)
1. Why object orientation — the software crisis
2. Classes and objects — the fundamental ideas
3. Fields, methods, constructors
4. Encapsulation — public, private, protected, package
5. Getters, setters, and why they matter
6. `this` reference and constructor chaining
7. `static` — class-level fields and methods
8. `final` — constants, immutable objects, final methods
9. Object lifecycle — creation, references, garbage collection

### Unit 2 — Inheritance and Polymorphism (9 lectures)
1. Inheritance — the `extends` relationship
2. Method overriding and dynamic dispatch
3. The `super` keyword — constructors and methods
4. Access modifiers in inheritance
5. Polymorphism — compile-time vs runtime
6. Abstract classes and abstract methods
7. Interfaces — contracts without implementation
8. Multiple inheritance via interfaces
9. `Object` — equals, hashCode, toString

### Unit 3 — Exceptions and Generics (9 lectures)
1. Errors vs exceptions
2. Checked vs unchecked exceptions
3. Try, catch, finally
4. Try-with-resources
5. Throwing and propagating exceptions
6. Custom exception classes
7. Introduction to generics
8. Generic classes and generic methods
9. Bounded types and wildcards

### Unit 4 — Collections and I/O (9 lectures)
1. The Java Collections Framework — overview
2. `List`, `Set`, `Map` — when to use each
3. `ArrayList`, `LinkedList` — trade-offs
4. `HashSet`, `TreeSet` — order and equality
5. `HashMap`, `TreeMap` — key-value mapping
6. Iterating collections — iterators and for-each
7. Streams API — filter, map, reduce
8. File I/O — reading and writing text files
9. Serialisation and JSON basics

### Unit 5 — Design and Best Practices (9 lectures)
1. Coupling and cohesion
2. SOLID principles — S and O
3. SOLID principles — L, I, D
4. Composition vs inheritance
5. Design patterns — singleton, factory
6. Design patterns — observer, strategy
7. Unit testing with JUnit
8. Refactoring — code smells and fixes
9. Building a real application end to end

## Practical Labs (18)

1. Set up Java, JDK, and a build tool (Maven or Gradle)
2. First class — define, instantiate, print
3. Encapsulation — a `BankAccount` with private balance
4. Static counter — track how many objects exist
5. Immutable `Point` and `Money` classes
6. Inheritance — `Shape` base and circle/rectangle subclasses
7. Method overriding — area and perimeter polymorphism
8. Abstract class `Shape` with abstract `area()`
9. Interface `Drawable` and multiple implementers
10. Override `equals`, `hashCode`, `toString` on `Student`
11. Exception handling — a robust calculator
12. Custom exception — `InsufficientFundsException`
13. Generic `Box<T>` and `Pair<A,B>`
14. Collections — sort a list of students
15. Streams — filter and map student data
16. File I/O — read CSV, parse, output summary
17. JUnit — test `BankAccount` and `Shape`
18. Design patterns — a small library using singleton + factory

## Assignments

1. Class design — model a small domain (library, bank, school)
2. Inheritance and polymorphism — shapes and animals
3. Exceptions — robust file reader with error handling
4. Collections — inventory tracker with HashMap
5. Final project — a console application using OOP and design patterns
