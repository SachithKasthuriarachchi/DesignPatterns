## Question 1:

### What is Design Pattern?

- Design patterns provide a template solution to core of some recurring problems in a way they are re-usable.

## Question 2:

### List down four essential elements of patterns.

- Name of the pattern
- Problem
- Solution
- Consequences

## Question 3:

### What is MVC Architecture?

- MVC is Model-View-Controller architecture
- Model is the application object. View is the screen representation of the UI and the controller defines how the view
  reacts to user input.
- Before MVC, people put M, V and C together when designing a user interface. MVC decoupled those

## Question 4:

### What are all the criteria used to classify design pattern?

- Scope of the design pattern
- Purpose of the design pattern

## Question 5:

### Name three classifications of design patterns based on purpose of the design pattern.

- Creational Patterns
- Behavioural Patterns
- Structural Patterns

## Question 6

### Name two classifications of design patterns based on scope of the design pattern.

- Object scoped
- Class scoped

## Question 7

### Write notes on Object, Methods, Requests.

Object: Object handles requests via its methods. The only way an object executes an operation is via a request and
operations are the only way that is capable of changing the object's internal state. Object encapsulates its data and
operations.

Methods: Methods handle requests. A method has a name, input parameters and output type which together known as the
signature of a method.

## Question 8

### What is encapsulation?

- Encapsulation describes binding data and operations which work on that data in a single unit.

## Question 9

### What is Facade and Flyweight patterns?

- Facade pattern describes how to model complete subsystems as objects
- Flyweight pattern describes supporting hugh number of objects at their finest granularities

## Question 10

### Write notes on operation's signature in an object

- Operation has a name, input parameters and an output type. All of these together known as the signature of the
  operation.

## Question 11

### Write notes on interfaces in Object oriented systems.

- Interface defines the type of object.
- Set of all the signatures of the object's operations is called the interface to the object.

## Question 12

### What is dynamic binding of an object?

- Runtime association of a request to an object and one of its operation
- Dynamic binding allows you to exchange one object for another object with same type at the runtime. (This is known as
  polymorphism)

## Question 13

### Write notes on abstract class.

- Abstract class contains mostly abstract methods where there implementation is done by the class which implements the
  abstract class. Abstract classes can contain methods with their implementation too. These types of classes cannot be
  instantiated.

## Question 14

### Define concrete classes

- Classes that are not abstract are known as concrete classes

## Question 15

### Define Mixin class

- Mixin class provides optional functionalities or an interface to a class.
- Mixin class requires multiple inheritance
- Mixin class cannot be instantiated

## Question 16

### Name two techniques for reusing functionality in Object oriented systems.

- Reusing by subclassing
- Reusing by object composition

## Question 17

### Define white-box reuse

- Reusing by subclassing is known as white-box reuse since the derived class has the visibility to its parent class's
  methods.

## Question 18

### Define black-box reuse

- Reusing with object composition is known as black-box reuse.
- Objects are composed to get more complex functionality.
- Internal details of objects are not exposed

## Question 19

### What are all the disadvantages of class inheritance.

- Subclass has the visibility to its parent class methods. Therefore, this breaks the encapsulation.
- Class inheritance belongs to compile-time and it is static.
- When we have to do some changes to the parent class, it may affect all the sub-classes too

## Question 20

### What is delegation?

- In delegation, an object delegates its request to another objet which has appropriate methods to handle such requests.
- Delegation includes redirects.
- Delegation involves two objects. Receiving object and the delegate object.

## Question 21

### What is the main advantage of delegation?

- It enables us to compose behaviours at runtime and to change the way they are composed

## Question 22

### What are all the disadvantages of delegation?

- It may reduce the readability of the code

## Question 23

### Write notes on Acquaintance relationship of objects.

- Acquaintance means two object can request functionalities from each other but, they are not responsible for each other.
- It enables loose coupling compared to aggregation which tightly couples the object
- In aquaintance, one object can survive without the other.