# OOP_Quiz

# Polymorphism
1. What does the word 'polymorphism' mean?

It means many shapes.

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.

In the context of object-oriented programming, polymorphism refers to the ability for object types to be cast to other types.

public class Guitar implements IStrum {
        *code*
    }


3. What can we use to implement polymorphism in Java?

In Java we can use interface implementation and Class inheritance

4. How many 'forms' can an object take when using polymorphism?

Classes utilising inheritance can hold two forms but with the use of interfaces there is no practical limit.

5. Give an example of when you could use polymorphism.

We can use polymorphism 


# Composition
6. What do we mean by 'composition' in reference to object-oriented programming?

Refers to the "Has A" principle i.e we can compose a system from child classes of which the parent class can be derived from i.e a Stereo class HAS A CD Player (class) and a radio (class).

7. When would you use composition? Provide a simple example in Java.

To group components under a common class ie, Stages in a venue.

public class Venue(

    private ArrayList<Stages> stages;
    
    public Venue(ArrayList<Stages> Stages){
        this.stages = new ArrayList<>();
)

8. What is/are the advantage(s) of using composition?

It allows code to be de-coupled and more flexible for refactoring or system expansion.

9. When an object is destroyed, what happens to all the objects it is composed of? They are also destroyed. 
