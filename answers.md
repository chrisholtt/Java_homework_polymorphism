q. What does the word 'polymorphism' mean?
a. Polymorphism means "many forms" and it occurs when we have many classes related to each other through "inheritance".

q. What does it mean when we apply polymorphism to OO design? Give a simple Java example.
a. In Java we can have a class called staff that takes in a name and a age value. There could then be another class called manager that inherits from staff but takes in an extra parameter, such as salary.

q. What can we use to implement polymorphism in Java?
a. Classes that "extend" from another class

q. How many 'forms' can an object take when using polymorphism?
a. An object can be two forms.

q. Give an example of when you could use polymorphism.
a. A shape class that contains color and another class that inherits from shape class called "triangle" that has another atribute on it called "numberOfPoints".


Composition and Aggregation

q. What do we mean by 'composition' in reference to object-oriented programming?

a.  The Composition between two entities is done when an object contains a composed object, and the composed object cannot exist without another entity. 

q. When would you use composition? Provide a simple example in Java.

a. A Car class that has a "has a" with an Engine and has a "is a" relationship with a Vehicle class.

q. Give a difference between composition and aggregation?

a. The difference between aggregation and composition is that aggregation is an association among two objects that have the “has a” relationship while the composition is a special type of aggregation that describes ownership.

q. What is/are the advantage(s) of using composition/aggregation?
a. There is principle, which sounds like “favor object composition over class inheritance”. Composition over inheritance in OOP is the principle that classes should achieve polymorphism and code reuse by composition, instead of through inheritance.
q. When using composition, when an object is destroyed, what happens to all the objects it is composed of?
a. All of the objects it is composed of are also destroyed.
q. When using aggregation, when an object is destroyed, what happens to all the objects it is composed of?
a. Nothing, the parent class can exist without its children classes.