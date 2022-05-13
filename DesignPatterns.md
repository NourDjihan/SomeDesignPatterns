### Template Pattern:
In a a class or an abstract class, there is a method (template, concreate, abstract or hook) that defined the general behavior of the subclasses. 
The details behavior is or not to be specified by the subclasses.

## A Concreate method: 
is to be implemented by the superclass and not redefined in the subclasses.
## An Abstract method:
is to be implemented by the subclasses only and not the superclass.
## A hook method: 
An empty method which is or not to be redefined in the subclasses.
## A templae method: 
it can combine all of them in the same method. Where each of the called methods have Self as a receiver. Self represents the how are these
methods perfom their tasks.

###
