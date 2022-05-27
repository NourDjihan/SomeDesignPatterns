# Template Pattern:
Template method design pattern is to define an algorithm as a skeleton of operations and leave the details to be implemented by the child classes. The overall structure and sequence of the algorithm are preserved by the parent class. 
In a class or an abstract class, there is a method (template, concreate, abstract or hook) that defines the general behavior of the subclasses. 
The details behavior is or not to be specified by the subclasses.

## A Concreate method: 
is to be implemented by the superclass and not redefined in the subclasses.
## An Abstract method:
is to be implemented by the subclasses only and not the superclass.
## A hook method: 
A hook method defines a default behavior. This behavior can do nothing (Do nothing hook). It can or not be redefined in the subclasses.
## A templae method: 
it can combine all of them in the same method. Where each of the called methods have Self as a receiver. Self represents the how are these
methods perfom their tasks.

### Facade attern:
Provides a unified interface to a set of interfaces in a subsystem, making the subsystem easier to use. Henceforth, subsystems are designed for flexibility and extensibility. This provides a common mode of understanding the subsytem in general without having to read the source code of each and verey subclass.
