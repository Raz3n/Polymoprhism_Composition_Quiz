# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?

  - Polymorphism is the ability of an object to take on different forms.


2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.

  - An example would be in using interfaces to give specific types of behaviour to
    different objects i.e. an interface called IFly can give flying behaviours to
    different flying objects like Dragons, broomsticks, etc.

3. What can we use to implement polymorphism in Java?

  - We can use Interfaces to implement polymorphism.

4. How many 'forms' can an object take when using polymorphism?

- An object can take multiple 'forms' with polymorphism.

5. Give an example of when you could use polymorphism.

  - see Q.2.

  - Another example would be using an Interface called ISwim which could give
    swimming behaviours to different objects that could swim i.e Humans, fish, Platypus.

# Composition

6. What do we mean by 'composition' in reference to object-oriented programming?

  - Composition describes a class that references one or multiple objects of
    other classes in instance variables. i.e. a HAS-A relationship where an object
    is made up of one or multiple objects.

7. When would you use composition? Provide a simple example in Java.

  - You would use composition in Java for example when Object A only needs some
    of the behaviours of from Object B rather than all of them, in which case we
    would use inheritance for getting all the behaviours.


8. What is/are the advantage(s) of using composition?

  - One advantage of composition is the ability to re-use code without having to
    create an IS-A association as we would in inheritance.

  - (From further looking online) It can also help with designing of API's. As when
    you create a class, you can decide whether or not the referenced classes become
    part of the API or if you want to hide them.

9. When an object is destroyed, what happens to all the objects it is composed of?

  - When an object is destroyed, all the objects it is composed of are destroyed too.
