<h1> <u> Software Design Methodologies </u>

<h2> Task 1 </h2>
<p><strong>Coupling</strong> - The degree of independence or connection between modules in a software system. Essentially, it measures how much one module is dependent on another. In software design, the aim to is to achieve low coupling. This ensures systems are flexible, maintainable, and conprehensible. </p>

<p><strong>Cohesion</strong> - The degree to which the responsibilities and functions within a module are related and focused on a single, well-defined purpose or task. It measures how well a module's internal elements work toward a common goal. </p>

<h2> Task 2 </h2>
<p><strong>Top-down</strong> design starts with the overall system or problem statement and breaks it down into smaller sub-problems or modules. These sub-problems are further decomposed into smaller modules until the lowest-level modules are simple enough to be implemented directly. </p>

<p><strong>Bottom-up</strong> design begins with the smallest and simplest modules or components, which are gradually combined to create higher-level structures and, eventually, the complete system. </p>

<p>A function oriented design primarily focuses on designing a system or software based on functions or procedures. In this design approach, the system's functionality is decomposed into functions or subroutines. These functions encapsulate specific tasks or processes and can be called or invoked as needed. In a top-down design, the high-level functions or procedured that the system needs to perform are identified, then decomposed into smaller, more specific functions. This aligns with a function-oriented design approach. </p>

<h2> Task 3 </h2>
A class diagram is most useful in the context of Object-Oriented Design as they are useful for modelling and visualising the structure, relationships, and behaviours of classes in an object-oriented system, making them an essential part of the design and documentation process in this context.

<h2> Task 4 </h2>
<p><strong>Encapuslation</strong> - The concept of containing data and methods that operate on that data into a single unit known as a class, while hiding the internal details of how the class works to provide a clear interface for interacting with it.

<strong>Abstraction</strong> - Simplifying complex reality by modelling classes based on the essential attributes and behaviours, allowing a clear focus on what an object does rather than how it does it.

<strong>Inheritance</strong> - Enables the creation of new classes based on existing classes, inheriting their attributes and behaviours, which promotes code reusability and heirarchy.

<strong>Polymorphism</strong> - Allows objects of different classes to be treated as objects of a common superclass, enabling method calls and behaviours to vary depending on the specific class, enhancing flexibility and extensibility in Object-Oriented Programming.

<h2>Task 5 </h2>
<p>Strategy pattern - A behavioural design pattern that defines a family of algorithms, encapsulates each one, and makes them interchangeable. It allows a client to choose an algorithm from a family of algoirthms at runtime, without altering the code that uses the algorithm. </p>

<p>In object-oriented systems, a set of concrete strategy classes would be created, that implement the strategy interface or inherit from the strategy abstract class. Each concrete strategy class represents a specific algorithm or behaviour. The context class has a reference to the strategy or abstract class, and it can switch between different strategies at runtime by setting its strategy reference to an instance of the desired concerete strategy class. In a functional system, the same seperation of concerns and flexibility can be achieved, but without classes and objects, relying on functions and function composition instead. </p>

<h2> Task 6 </h2>
For creating a versatile online payment system that isn't tied to a particular sector and can work equally well in various scenarios, I believe an Object-Oriented Design methodology, would be the most suitable. Object oriented design is better suited to handling complex, adaptable, and extensible systems, which aligns with the requirements of an online payment system that must serve multiple sectors. Whereas, Function-Oriented design is less suitable in this context because it tends to focus on individual functions or procedures, which can lead to a less organised and less modular approach, making it more challenging to adapt to the diverese requirements of different sectors. To conclude, OOD is the more appropriate design methodology for creating a versatile online payment system that can cater to a wide range of sectors while maintaining adaptability, modularity, and maintainability. 