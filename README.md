# SOLID

Single Responsibility Principle – Classes or modules should only have one reason to change. This means that it only has one functionality. Example, if you had a class that changed content and formatting that would be two functions and would break this principle. You should create two separate classes where one changes content and the other does formatting. This makes it easier for a coder to see where errors are happening, make specific changes to one function, and test the code.

Open/Closed Principle – It is possible to add fields to existing data structure while the overall classes doesn’t need to be modified. This require good forethought and having your code be able to input additional behavior with simple field additions. The goal is to make your class reusable. This feeds into the Single Responsibility Principle.

Liskov Substitution Principle – Should be able to sub in sub classes for their parent class without effect the callers of the code. You shouldn’t have methods named for one modification make a change for another attribute or method. It will create changes that may be hard to track and create surprise results. 

Interface Segregation Principle – client shouldn’t be forced to depend on methods they don’t use. Implementation of this principle creates robustness and add distinction to your methods. The reduction in dependencies allows errors to be traced more easily. 

Dependency Inversion Principle – Having higher level object not be dependent on lower level details. This is usually achieved through implementation of the Open/Closed Principle. The goal is to decouple high-level functionality from low-level implementation details. This allows us to easily identify specific details that we want to change if we need to.
