# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?

  Can be specified by different types (can use interfaces as types). For example, an object can be added to a collection specifies type as a parent class that the object inherits from, or interface that the object implements.

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.

  Polymorphism in OO allows similar objects to behave in particular common way. They can be collected together through this shared behaviour but, when called from the collection, can only perform the actions that are common.

  Example:
  All animals multiply and respire. This means fish, bears, and amoebas can be connected through these common actions. A Collection<Animal> can be made to take fish, bears, and amoebas but, of any object in that collection, we can only ask it to multiply or respire as, without further checks, we can't tell what we have taken out of the collection, only that it is an animal.

3. What can we use to implement polymorphism in Java?

We can use inheritance and interfaces to create polymorphic classes.

4. How many 'forms' can an object take when using polymorphism?

It can only take one through inheritance but many through interfacing.

5. Give an example of when you could use polymorphism.

Modelling the tree of life.

# Composition

6. What do we mean by 'composition' in reference to object-oriented programming?

7. When would you use composition? Provide a simple example in Java.

8. What is/are the advantage(s) of using composition?

9. What happens to the behaviours when the object composed of them is destroyed?
