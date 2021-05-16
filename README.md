# reimagined-design-patterns

Give a summary description of Four design patterns that you choose from the following design patterns: **Adapter,  Builder, Composite, Decorator, Observer, Interpreter, State, Mediator, Memento, Prototype, Proxy**. In your summaries say:

- what kind of problem(s) you can solve with that pattern and when you use it, maybe with a short example
- how the pattern works, what the basic idea of the pattern is
- what the main advantage and what the the main disadvantage is of using this pattern
- Write a short summary for each of the four patterns, about half a page for each pattern (rather less than more). 

> Do not add diagrams, and do not try to give a complete description of the patterns as found in the books. Rather think of how you would explain the essential ideas of these patterns in a few sentences to a colleague while drinking coffee.


ADAPTER:

--> Short Summary :
  Adapter is a design pattern type which allows two incompatible classes to work together by acting as a bridge. This basically converts the interface of one class in line with the expectation of the client's interface.
  
--> What kind of problem(s) you can solve with that pattern and when you use it, maybe with a short example?
  This pattern will be used when the client's interface expectation is different from the Adaptee's interface - but, the client and adaptee should work together to achieve a purpose. Here, as mentioned above, the adapter converts interface of adaptee as per the expectation of the client's interface.
  Example: Power adapters which we use when we are abroad i.e. the socket in abroad(like Germany or US) will be different and doesn't suite to our device's power chords. So, we will use a adapter which converts the socket interface suitable for the device's power line.
  
--> Advantages:
  1. Easy extension and reusage of existing code
  2. Modifying only the adapter class is sufficient
  
--> Disadvantages:
  1. Increases the code complexity

DECORATOR:

--> Short Summary:
  Decorator is a design pattern which dynamically changes the functionality of an object at runtime without modification of the exiting functionality or implementation.
  
--> What kind of problem(s) you can solve with that pattern and when you use it, maybe with a short example?
  This pattern will be used when we need to add a new functionality to an already existing implementation due to many reasons like when the existing implementation is rigid and doesn't provide ease of extension.
   Example: We have a website where it shows the list of products. Now we need to provide sort / filetr functionality for the same listing of products. Here we can go for a decorator.
   
--> Advantages:
  1. Provides flexibility of adding a new feature to an existing functionality without the need of modifying it
 
--> Disadvantages:
  1. The decorator should be designed inline with the existing functionality.

MEDIATOR:

--> Short Summary:
  Mediator is a design pattern which help reduce the communication complexity between different objects i.e. it basically mediates the message from one object in a form where the receiver objects can understand.
  
--> What kind of problem(s) you can solve with that pattern and when you use it, maybe with a short example?
  This design pattern can be used in an interconnected system where the complexity is high.
  Example: Instrument Cluster in vehicles. This receives the crucial parameter values from engine ECU and displays warnings/ icons when the values are not within the recommended range - so that the driver/service-man can understand the problem.
  
--> Advantages:
  1. Provides he benefit of loose coupling
  2. Faster Communication
--> Disadvantages:
  1. Possibility of increase in code complexity

OBSERVER:

--> Short Summary:
  Observer is a design pattern which observes and automatically notifies the dependent object i.e. if a change has been observed in one object then this change shall eb notified to all the dependent objects.
--> What kind of problem(s) you can solve with that pattern and when you use it, maybe with a short example?
  This design pattern shall be normally used to establish a one to many dependent relationships.
  Example: When there is any change in the Employee policy, then a notification has to be provided to all the associates of the company.
  
--> Advantages:
  1. Possibility of establishing a proper communication between subject & observer without changing any of them.
  
--> Disadvantages:
  1. Increase in code complexity
