# Software Design Methodologies

## Task

**1. What do we mean by coupling and cohension when discussing stuctured design?**

- **Coupling** refers to the degree in which different components (i.e. classes) interact with each other.
Within structured design, a low coupling between modules is desired to ensure a modular system in which modules are loosely connected with little dependence on others.

- **Cohesion** refers to the degree in which different elements with a module interact with each other to perform a single purpose.
In structured design, a high cohesion within modules is required to ensure each module focuses on closely related tasks making them more maintable.

**2. What is the difference between top-down and bottom-up design? Which best describes a function oriented design?**

- **Top-down design** begins with a high-level overview of the system with no details which gradually becomes refined with more detail and definitions until there is a sufficient amount of information to validate the model.

- **Bottom-up design** starts with individual compoments of the system being specified in detail which gradually gets integrated together to form larger components until an overal system is formed.

A function oriented design is best aligned with a bottom-up design approach.

**3. In which design methodology would a class diagram be most useful?**

A class diagram would be most useful in **object-oriented design** as this design methodology focuses on objects and classes. The class diagram would serve as a visual aid of the building blocks of the system.

**4. What are the four pillars of object oriented programming? Give a single-sentence description of each.**

**1. Encapsulation** - wrapping data and methods into an object to hide it's internal structure.

**2. Inheritance** - creating a new class from an exisiting one allowing it to inherit attributes and methods. 

**3. Polymorphism** - allows an object to take multiple forms so it can be used interchangeably when implementing a particular interface.

**4. Abstraction** - simplifying complex systems by hiding an object's internal strcture by creating an abstract class and interface.

**5. What is the strategy pattern? How would its implementation differ between a functional and object oriented system?**

**The stragery pattern** is a behavioural design pattern allowing the alteration of an object's behaviour through encapsulation.

**Object-oriented systems** use objects to represent stratergies therefore, to change stratergies we change objects and encapsulation occurs with classes.

Whereas **functional systems** use functions to represent stratergies therefore, to change stratergies we change functions and encapsulation occurs with function scope.

**6. Imagine your creating a new online payment system. In order to gain maximum market share it can't be tied to a particular sector - it needs to work just as well when ordering a takeaway as when buying a new coat. Which design methodology would you suggest following? Give some justification for your decision.**

I would suggest **object-oriented design** as this deisng methodology would provide a strctured and flexible system which can adapt to different sectors. 

Justifications : 
- **Adaptable to change** - can change method and attribute implementations without impacting the main code.

- **Encapsulation** - can encapsulate sensitive data within an object. This is important due to a payment system requiring data protection.

- **Easy maintenance** - can update specific components without impacting other components or the main code.

- **Reusability** - can reuse the system due to inheritance and composition in object-oriented design.

👩‍💻👩‍💻👩‍💻👩‍💻