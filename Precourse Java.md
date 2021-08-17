

# Precourse Java

Once we begin to understand a programming language and what it offers us as developers, we also need to understand the big picture regarding development in practice and building applications at scale. 

With mobile development in both iOS and Android, you will encounter many of the same challenges and problems for developing either type of application. 

As a part of the precourse work, we talk about high level concepts that extend past iOS development. Even more, these same ideas extend past Android mobile development and apply to all levels of computer programming. As you hit landmarks in your learning regarding mobile development, having the foundational knowledge will make learning more applicable and useful. 

As developers, we will be covering the following questions as it applies to iOS and Android development, but more importantly, how it applies to developers as a whole. 

#### What are we building?

Full Stack Applications utilizing modern technologies -  **Databases, APIs, Servers,** and more!

#### How?

Using **Object Oriented** development techniques to help modularize and enhance code. There are multiple **programming paradigms** and we will go over them. This means that there are multiple ways to accomplish the same code. With proper **access control**, we have access to classes so that we can create objects. 

#### To Solve What Problem?

We will go over common **design pattern** solutions to help solve common programming problems

#### What's the point?

Computers can solve problems faster than humans and that's the power of computer programming. We will go over approaches to speed up computer performance for searching and optimization, analyzing **Big O** (worst and best case peformance for our computers). Computers can do many things at once, and with this in mind, we will go over **concurrency**. 

#### Are there multiple ways to do the same thing?

Yes, there are multiple ways to write the same code. But, we can write our code in a way to make it more powerful, more effecient, more organized, and more useful.

We will learn **Design Patterns** in Java to start wrapping our head around design patterns. 

#### Do we need to create everything ouselves?

We should utilize the community for development purposes and leverage **frameworks** and **libraries** to create great work. Great programmers don't always recreate the wheel. 

# Using Java

We will be using Java to demonstrate coding concepts that extend past Swift and Kotlin. Since both Swift, Kotlin, and Java are C based langugages, Java emerges as a language that is perfect for this learning opportunity. 

It's important to note that Java is more verbose than Swift and Kotlin. With this in mind, be sure to focus on the main principles at hand and don't get too caught up on the small incatricies of Java.

## Full Stack Development

When we are building applications with Swift and Kotlin, we will be building full stack applications. The **front end** of the application is the client side (user-facing) and the **backend** is the server side of an application. 

#### Front End

The visible part of an application facing the user (responsible for user experience)

-   Front End Langague Examples: HTML, CSS, JavaScript
-   Front End Famework Examples: Angular, React

#### Back End

What the client doesn't see. Think databases, backend logic, APIs, and servers. Take the example of a user submitting form data to a website. The user types in their email and password and this gets processed by the server and stored in a **database**. None of this processing or storage is seen by the user.

So with the back end, we have backend languages, servers, databases, and APIs. Let's go over these. 

#### Backend languages

Some examples of backend languages include Java, Python, PHP, Node.js, JavaScript

#### Server

-   a computer or computers that send data over a network and receives and responds to requests
-   Just about any computer can function as a server. But, computers suited for this particular need do a better job of handling many requests at once for a very long time. 

#### Database

A database is simply a collection of data stored in an organized way

-   Stored on the server
-   Types of Databases:
    -   **NoSQL databases** 
        -   are designed to handle the more complex, unstructured data, (such as texts, social media posts, photos, videos, email)
        -   stores unstructured or semi-structured data, often in key-value pairs or JSON documents.
    -   **Relational databases** 
        -   store related data tables (relational)
        -   common technology for decades

## Database Assignment

Given the following data, create a database structure for a NoSQL Database and a Relational Database.



#### API

APIs are not meant to be seen or used by the end user. Instead, an API generally uses RESTful design to give others a large amount of organized data (usually in the form of JSON or XML)

-   RESTful APIs follow a set of rules regarding how they should send and receive information (architectural style)
-   a set of programming instructions and functions used to access a website or web-based software application.



# Android Studio (For Java Development)

Now that we have some of the basic concepts down for programming, lets jump right in and download Android Studio. The reason we are using Android Studio for our learning purposes instead of an IDE like Eclipse is that it makes setting up our environment easy (such as downloading the SDK and readying our environment for development)

Note: we are not building Android applications at this point. Instead, we are using Andriod Studio as our IDE (Integrated Development Enivronment) so we can build on our development skills!

**For Mac Users:** 

1.  Go to https://developer.android.com/studio and click download Android Studio (with Intel or Apple Chip depending on if you have an older Mac vs Newer M1.)

2.  Launch the Android Studio DMG file.

3.  Drag and drop Android Studio into the Applications folder, then launch Android Studio.

4.  Select whether you want to import previous Android Studio settings, then click **OK**.

5.  The Android Studio Setup Wizard guides you through the rest of the setup, which includes downloading Android SDK components that are required for development.

    ![](https://hosting.photobucket.com/images/i/jhuntcd/wizard.png?width=285&height=175&crop=fill)

6.  Create a new project (Phone and Tablet) with **No Activity** 

    ![](https://hosting.photobucket.com/images/i/jhuntcd/newproject.png?width=285&height=175&crop=fill)

    



### Creating a new Java Module and Class

You can have Java modules and Android modules in the same project and also have the ability to compile and run Java modules as stand alone Java projects.

1.  Open your Android project in Android Studio. If you do not have one, create one.
2.  Click **File > New Module**. Select **Java Library** and click **Next**.
3.  Fill in the package name, etc and click **Finish**. You should now see a Java module inside your Android project.
4.  Add your code to the Java module you've just created.
5.  Click on the drop down to the left of the run button. Click **Edit Configurations...**
6.  In the new window, click on the plus sign at the top left of the window and select **Application**
7.  A new application configuration should appear, enter in the details such as your main class and classpath of your module.
8.  Click **OK**. Now if you click run, this should compile and run your Java module.


![](https://hosting.photobucket.com/images/i/jhuntcd/setup.png?width=285&height=175&crop=fill)

# Programming Paradigms

#### Object Oriented Programming

We aim to be **full stack developers** who keep our code modular and organized. One of the ways we can achieve this is by using OOP, or Object Oriented Programming design (programming architecture built upon the concept of classes and objects)

-   Break down a programming task into objects that expose behavior (methods) and data (members or attributes) using interfaces

#### Procedural Programming

Often, the terms "procedural programming" and "imperative programming" are used synonymously

#### Functional Programming

Functional programming languages support (and heavily use) first-class functions, anonymous functions and closures

#### Reactive Programming

# Application Architecture and Design

# Design Patterns

As we develop code with Object Oriented principles in mind, programmers have developed best practices and techniques to solve common problems. Design patterns often solve a particular problem and offer a solution. 

In both iOS and Android development, we will encounter different design patterns. In this section, we will offer some common programming problems and how to solve them with design patterns

## Types of Design Patterns

#### Creational

class instantiation or object creation

#### Structural

organizing different classes and objects to form larger structures and provide new functionality

#### Behavorial

identifying common communication patterns between objects and realizing these patterns

## Model View Controller

#### Model

The Model stores application data 

#### View

The View is reponsible for the user interface

#### Controller

Core application logic that creates the relationship between the view and the model 

-   gets informed of the user’s behavior and updates the Model when needed

## Delegation

Use Delegation in order to achieve the following

-   Delegation can be an alternative to inheritance.
-   Delegation means that you use an object of another class as an instance variable, and forward messages to the instance.

When you delegate, you are simply calling up some class which knows what must be done. You do not really care how it does it, all you care about is that the class you are calling knows what needs doing.

#### Example Using Delegation

Passing the responsibility to someone else. In OOP, delegation is when you pass a task of an object to another one. 

Let's imagine that we need to build an application and for that we need:

-   a coder
-   a designer 

We are looking for people who can code and who can design.. 

```java
class DelegationDemonstration {
  // we will add the main method here
}
interface WhoCanCode {
    void writeCode();
}
interface WhoCanDesign {
    void design();
}
```

Now, we are going to hire an employee who is capable of doing both of these (coding and designing). This employee must implement the methods from our interfaces. 

```java
class Employee implements WhoCanCode, WhoCanDesign {
    @Override
    public void writeCode() {
    }
    @Override
    public void design() {
    }
}
```

This employee is smart enough to **delegate** responsibility to someone else. 

Let's say we are searching for a coder, and we find this coder (this person is a Swift coder)...

Notice the **implements** keyword. This is how we implement the methods from an interface!

```java
class SwiftDeveloper implements WhoCanCode {
    @Override
    public void writeCode() {
        System.out.println("I'm writing Swift Code");
    }
}
class UXDesigner implements  WhoCanDesign {
    @Override
    public void design() {
        System.out.println("I'm designing UX");
    }
}
```

Now, what the Employee will do.. it will take an instance of WhoCanCode ...coder and designer

Whenever there is an employee, it will take a coder and a designer, and pass that resposibility to them. 

```java
class Employee implements WhoCanCode, WhoCanDesign {
    WhoCanCode developer;
    WhoCanDesign designer;

    public Employee(WhoCanCode developer, WhoCanDesign designer){
        this.developer = developer;
        this.designer = designer;
    }

    @Override
    public void writeCode() {
        developer.writeCode();
    }
    @Override
    public void design() {
        designer.design();
    }
}
```

To execute this, we need a main method!

```java
public class DelegationDemonstration {
    public static void main(String[] args){

        SwiftDeveloper switDev = new SwiftDeveloper();
        UXDesigner designer = new UXDesigner();

        Employee james = new Employee(switDev,designer);

        james.writeCode();
        james.design();
    }
}
```

Now, we could easily add in a new Kotlin developer too!

```java
class KotlinDeveloper implements WhoCanCode {
    @Override
    public void writeCode() {
        System.out.println("I'm writing Kotlin Code");
    }
}
```

and update the main method ...

```java
public class DelegationDemonstration {
    public static void main(String[] args){

        SwiftDeveloper switDev = new SwiftDeveloper();
        UXDesigner designer = new UXDesigner();
        KotlinDeveloper kotlinDev = new KotlinDeveloper();

        Employee james = new Employee(switDev,designer);
        Employee david = new Employee(kotlinDev,designer);

        james.writeCode();
        james.design();

        david.writeCode();
        david.design();
    }
}
```

###### Delegation Pattern Summary

-   Reduce the coupling of methods to their class
-   Use for components that behave identically, but realize that this situation can change in the future.
-   If you need to use functionality in another class but you do not want to change that functionality then use delegation instead of inheritance.

Here's the full code for your clarification..

```java
public class DelegationDemonstration {
    public static void main(String[] args){

        SwiftDeveloper switDev = new SwiftDeveloper();
        UXDesigner designer = new UXDesigner();
        KotlinDeveloper kotlinDev = new KotlinDeveloper();

        Employee james = new Employee(switDev,designer);
        Employee david = new Employee(kotlinDev,designer);

        james.writeCode();
        james.design();

        david.writeCode();
        david.design();
    }
}

interface WhoCanCode {
    void writeCode();
}
interface WhoCanDesign {
    void design();
}

class Employee implements WhoCanCode, WhoCanDesign {
    WhoCanCode developer;
    WhoCanDesign designer;

    public Employee(WhoCanCode developer, WhoCanDesign designer){
        this.developer = developer;
        this.designer = designer;
    }

    @Override
    public void writeCode() {
        developer.writeCode();
    }
    @Override
    public void design() {
        designer.design();
    }
}

class SwiftDeveloper implements WhoCanCode {
    @Override
    public void writeCode() {
        System.out.println("I'm writing Swift Code");
    }
}
class UXDesigner implements  WhoCanDesign {
    @Override
    public void design() {
        System.out.println("I'm designing UX");
    }
}
class KotlinDeveloper implements WhoCanCode {
    @Override
    public void writeCode() {
        System.out.println("I'm writing Kotlin Code");
    }
}
```

## Strategy Pattern

The Stategy Pattern defines a family of algorithms and encapsulates each one and makes them interchangable. So when we are using **OOP**, we wrap a **class** around this functionality, and makes them interchangable. We could use an **interface** here so that you could swap out these behaviors at any point in time. The strategy let's the algorithm **vary indepndently** from the clients that use it. 



Encapsulate a behavior into a class,  and make that class **interchangable** with other classes. This allows other classes to use it and use those low level **encapsulations** of behaviors, **without having to know how they are implemented or how they work**. 



Let's use the example of a person. 



People have different **behaviors associated with them**. 

-   All people can eat() and talk()

What would happen if we wanted to add the ability to jump for the person?

-   jump()



Not all people can jump. In this example, only some people can jump -- only athletes can jump. For this example, other types of people can't jump. (Obviously non athlete's can jump, but this is just a good imaginary example!)



![](https://hosting.photobucket.com/images/i/jhuntcd/stategy-person.png)



How do we accomplish this? 



We could add a jump function above. 

In the subclasses that don't allow jumping, we could **override** the jump method with something that has no behavior... maybe throw an exception? But this isn't the best way to do this. This isn't the OOP way. 



So what is the correct way? Take a look at these other class diagrams. 

<img src="https://hosting.photobucket.com/images/i/jhuntcd/strategy1.png" style="zoom:67%;" />



So we have the Athlete Person and the Scientist Person. 

So a Athlete Person is able to jump. It has the eat() function that it can override or inherit from the parent class.. It also has a jump() function. 



But the Scientist Person only knows how to eat, this person does not know how to jump. 



So how could we code this jump function in an OOP way? Maybe by using an interface or something that makes this more extensible? Yep!

So the Person would be the **superclass** and Athlete Person and Scientist Person would be the **subclasses**. 



Now we want to add jump functionality. We could create a Jumpable interface. And then the Jumpable interface would have a jump function, and the Athlete Person would implement the jump() function.

This would work, and many programmers would do this very thing! So it makes sense for OOP.



### The Problem With this implementation

But the problem with this implementation is .. what if we had a different subclass...

a Musician Person.



And the Musician Person (in this imaginary example) also needs to jump. We want the jump function to do the SAME thing that exists in the Athlete Person.

So then the Musician Person would also need to implement the jump function as well. 



That's not very reusable. We want to implement the jump function once, and then have that shared between all of the classes.



This is where the Strategy pattern comes in!



Recap: We have a Person superclass, and we want to implement the jump function for some if its subclasses. A natural way to do this is with an **interace** called Jumpable with a jump function. For the **classes** that want to implement jumpable interface, they can have their own jump function.



The problem - Now any other class that want's the same jump funciton needs to redefine the same jump function used in the other classes. This isn't reusable.



### The Solution - Strategy Pattern

How do we fix it with the strategy pattern? 



<img src="https://hosting.photobucket.com/images/i/jhuntcd/strategy2.png" style="zoom:67%;" />

We can fix it by...

To make it so that we can take that jump behavior and **encapsulate** it .. put it into a class that we can reuse so that we can pass it around later. 



So we do that by using an interface. 



We will create an **interface** called JumpBehavior. So instead of tying the implementation of JumpBehavior into Athlete and Scientist Person, we wil pull that out and put it into an interface.

This Jump Behavior interface will have a **concrete implementation.** ( we can have as many implementations as we want)



#### Concrete Implementation

So people can Jump With Legs...right?  We could have an implementation of the JumpBehavior interface being called the JumpWithLegs implementation. This JumpWithLegs class.. it needs to implement something. 

Let's say that the JumpBehavior interface had a **function** called jump() that would be implemented by the JumpWithLegs class.

Now this JumpWithLegs **class** can define **jump()** in any way it wants, and then create an instance of this **JumpWithLegs** class, and pass that in to many different People such as the Athlete Person and the Musician Person. 



So now instead of recyling that jump function like we saw previously, we can just create that **single instance**, and pass that to the Person, and allow that to be used by any of the other classes.



So what do we need to change to our UML class diagram? 



#### How do we use the Strategy Pattern?

We need to add an instance level variable of type JumpBehavior in the Person class. 

Then we need to add a mechanism to invoke the JumpBehavior jump function. 

We can do this in many ways. We could create a performJump() function in the Person class which would call on the JumpBehavior method. 

Then we could change the constructor of the Person class to take in a Jump Behavior and pass that in at runtime. We could create a setter so that we could change this functionality later so..

If we had many different types of the implementing classes (of the jump behavior interface), these could be swapped out at runtime. 



So now, the Athlete Person, when its instantiated, can call the performJump() function, and it will jump. 

And the Scientist Person, if we have a different implementing class.... something called NoJump(), this type of person doesn't jump 



So the benefit is that we can create a single instance of this and just pass it along. 



### Strategy Code Example

Now let's use a real coding example!

`Person.java` - class

```java
abstract class Person {
    protected JumpBehavior jumpBehavior;
    public Person(JumpBehavior jumpBehavior){
        this.jumpBehavior = jumpBehavior;
    }
    public void performJump(){
        jumpBehavior.jump();
    }
}
```

-   So we have a Person class (abstract class)
-   We have an instance level variable called jumpBehavior of type JumpBehavior.
-   We have a constructor that takes in that jumpBehavior and sets that variable.
-   We have a performJump function that simply invokes the jumpBehavior jump function.



#### Abstract Classes

-    An abstract class is like a template, so you have to extend it and build on it before you can use it.
-   Abstract classes can not be instantiated



 `JumpBehavior.java` - interface

```java
interface JumpBehavior {
    public void jump();
}
```

-   the interface has a jump function. 



`JumpWithLegs.java` - concrete class

```java
class JumpWithLegs implements JumpBehavior {
    @Override
    public void jump() {
        System.out.println("I'm Jumping");
    }
}
```

-   Concrete class implements the JumpBehavior interface

-   We are ovveriding that JumpBehavior interface by actually implementing it.. printing out "I'm Jumping"



`AthletePerson.java`

```java
class AthletePerson extends Person {
    public AthletePerson(JumpBehavior jumpBehavior){
        super(jumpBehavior);
    }
    public void performJump(){
        jumpBehavior.jump();
    }
}
```

-   Athlete Person is an implemention of that abstract Person class. 

-   It uses super to call the base constructor 

-   Performs jump by calling the jumpBehavior's jump function.



If we take a look at the runner of this class... the Main function. What does this look like? 

`Main Method`

```java
class StrategyPattern {
    public static void main(String[] args){
        JumpBehavior jumpWithLegs = new JumpWithLegs();
        Person athletePerson = new AthletePerson(jumpWithLegs);

        athletePerson.performJump();
    }
}
```

-   We instatiate an instance of the JumpBehavior and create a new instance of the AthletePerson and passing in jumpWithLegs.

-   We only need to define jumpWithLegs once. 



### Strategy Conclusion

Remember that these behaviors can be interchanged with any implementing classes of type JumpBehavior.

So we can swap out the behaviors of these People at runtime using a setter function. The Strategy Pattern **encapsulates behavior** in a concrete class and lets you pass it around and resuse it!

​                                                                                                                                                                                                

Here's the full code below for the **Strategy Pattern** using people as an example!

```java
interface JumpBehavior {
    public void jump();
}
abstract class Person {
    protected JumpBehavior jumpBehavior;
    public Person(JumpBehavior jumpBehavior){
        this.jumpBehavior = jumpBehavior;
    }
    public void performJump(){
        jumpBehavior.jump();
    }
}
class JumpWithLegs implements JumpBehavior {
    @Override
    public void jump() {
        System.out.println("I'm Jumping");
    }
}
class AthletePerson extends Person {
    public AthletePerson(JumpBehavior jumpBehavior){
        super(jumpBehavior);
    }
    public void performJump(){
        jumpBehavior.jump();
    }
}
class StrategyPattern {
    public static void main(String[] args){
        JumpBehavior jumpWithLegs = new JumpWithLegs();
        Person athletePerson = new AthletePerson(jumpWithLegs);

        athletePerson.performJump();
    }
}
```




## Decorator

Attaches additional responsibilities to an object dynamically. Decorators provide a flexible alternative to subclassing for extending functionality. 

Typically when you want to add additional functionality to a class, you subclass → extend that class and override some of the functionality of the parent class. 

A classic example could be an Animal class that is a superclass and then a dog which is the subclass of the animal. You have a speak method on the parent class which you override in the dog class so when the dog speaks, it barks. If you have a cat subclass, when it speaks, it meows. This is typically how you would subclass in OOP and add additional functionality.



The decorator relies more on **composition** than **inheritance**. 



By using the decorator pattern you can impoersonate a class, and add additional funcionality without any users of that class knowing that its different from the original class. 

#### How we would code a problem WITHOUT the Decorator Pattern

Theme - Build a system to compute the cost of beverages for a coffee shop 



Coffee Beverages 

-   Dark Roast

-   Light Roast

-   Espresso

-   Latte

Prices added with condiments:

-   cream
-   almond milk
-   sugar

![](https://hosting.photobucket.com/images/i/jhuntcd/decorator.png)

Let's assume we have a **coffee** class, with two **attributes**:

-   price
-   description 

If we want to add different beverages now, for every beverage that we have on our menu (espresso, latte, etc. ), we now need to subclass coffee so that we can implement the cost and description function and override that behavior. 

So what would this look like?

-   **Espresso** needs to extend Coffee and override the cost and description function 
-   **Dark Roast** needs to extend Coffee and override the cost and description function 
-   **Light Roast** needs to extend Coffee and override the cost and description function 

#### The issues arises

Say we introduce the concept of **ingredients**. Now, we have an additional cost based on the ingredients:

-   cream 
-   milk 
-   sugar 

How do we incorporate the ingredients conecept into our relationship of classes?

-   We could create maybe a **List of Ingredients** 
    -   each of these types of ingredients (cream, milk, and sugar) would be a different implementation with different costs
-   When we build the Espresso object, we could add 2x sugar to the Espresso
-   In the Dark Roast, we could add 2x sugar, and maybe 1x milk 
    -   compute the cost based on the base cost of the Dark Roast, plus the sugar and milk added on

#### What's wrong with this approach?

The problem arises when we have a **class explosion** as you add all the different ingredients in. 

-   All of the possible combinations would add up to be a big mess!

#### Using the Decorator Pattern instead

We will use **composition** and **type matching** using **Abstract classes** to impersonate the Coffee class



Using the same example, let's walk through it again.

We have the **Coffee** object, which will have the following attributes:

**Coffee**

-   description
-   cost 

The coffee class is **Abstract**. Nobody will actually **instantiate an instance** of the coffee class. Instead, subclasses will use it as a **template**



Let's simplify things, and just use one drink to explain things. 

Let's say we have the **Espresso** beverage class. It has a different base cost than coffee. It's a little more expensive.

It's cost will be different

**Espresso** - implements the Coffee abstract class

-   Cost - $1.99



Introduce the **Coffee Decorator**! 

This class will impersonate coffee. It will **implement** Coffee, but it will allow us to **add ingredients dynamically**

Coffee Decorator will be abstract - we will never instantiate an instance of the decorator 

Coffee Decorator - allows for clever type matching in the implementation



**Coffee Decorator**



Next, we have the concept of adding **ingredients** 

Let's create a class called **WithMilk**, and **WithSugar**



For all the ingredients that we have, we can add additional classes just like this.



**WithMilk** implements the Coffee Decorator 

-   Cost - $0.50

**WithSugar** implements the Coffee Decorator 

-   Cost - $0.25

![](https://hosting.photobucket.com/images/i/jhuntcd/coffee_dec.png)

Both of these classes implement the Coffee Decorator. And the Coffee Decorator implements coffee, so WithSugar and WithMilk are of type Coffee... but through this relationship chain that we just built!



The basic idea is that now when we construct an instance of our Espresso, and we add additional things to it:

-   adding milk ($0.50)
-   adding sugar ($0.25)

These added costs will be **added dynamically** 

We will compute the cost function as the sum of all the ingredients, and the base - in this case - Espresso. 

#### Decorator Pattern Code

`Coffee.java`

```java
public abstract class Coffee {

    String description = "Unknown Coffee";

    public String getDescription() {
        return description;
    }

    public abstract double cost();
}
```

-   Coffee is abstract 
-   Defines a cost function which is abstract since coffee is abstract
-   Enforing that all subclasses need to define their cost function
-   anyone that implements the CoffeeDecorator, needs to implement the getDescription method and the cost function 

`Espresso.java`

```java
public class Espresso extends Coffee {

    public Espresso() {
        description = "Espresso";
    }

    @Override
    public double cost() {
        return 1.99;
    }

}
```

-   default constructor sets the description
-   base cost would be 1.99

`CoffeeDecorator.java`

```java
public abstract class CoffeeDecorator extends Coffee {
    public abstract String getDescription();
}
```

-   abstract class that extends Coffee 
-   CoffeeDecorator is coffee and you must override getDescription method

`WithMilk.java`

```java
public class WithMilk extends CoffeeDecorator {

    Coffee coffee;

    public WithMilk(Coffee coffee) {
        this.coffee = coffee;
    }

    @Override
    public String getDescription() {
        return coffee.getDescription() + ", Milk";
    }

    @Override
    public double cost() {
        return coffee.cost() + .50;
    }
}
```

-   this is where the decorator magic happens!
-   We have have to override desciption and cost
-   Keeps a refrence to the parent coffee object that it was called upon. We are holding reference to a coffee object
-   Whenever the constructor is called (WithMilk), we need to take an already existing coffee object (you would use espresso in this case since this is our base object), and we are holding a reference to it 
-   in getDescripton and cost, this is where the magic happens. We return the coffee's get description function, and we append Milk to it (in this case)
-   the object now contains an additional property (which is milk )

`WithSugar.java`

```java
public class WithSugar extends CoffeeDecorator {

    Coffee coffee;

    public WithSugar(Coffee coffee) {
        this.coffee = coffee;
    }

    @Override
    public String getDescription() {
        return coffee.getDescription() + ", Sugar";
    }

    @Override
    public double cost() {
        return coffee.cost() + .25;
    }
}

```

-   basically the same as Milk! 

`Decorator.java`

```java
public class Decorator {
    public static void main(String[] args) {

        Coffee espresso = new Espresso(); 
        printCoffee(espresso); 
        // we should see 1.99, and it should be espresso

        espresso = new WithMilk(espresso);
        printCoffee(espresso);
        // let's take that espresso object, and add some milk 

        espresso = new WithSugar(espresso);
        printCoffee(espresso);

    }

    private static void printCoffee(Coffee c) {
        System.out.println("Cost: " + c.cost() + ", Description: " + c.getDescription());
    }
}
```

-   let's test this out!

## Observer-Observable

One to one - delegation 

##### **One to many - observer**

When one object changes state, all of its dependents are notified and updated automatically. 



One object is the (subject) and we have multiple (dependents) that care about that object



Let's take the example of a **weather station** 

the weather station's job is to collect information like temperature, humidity, etc. 

This is the one.. in the **one to many** definition and we can call the one - the subject 



The **observers** will be **many**



The observers want the most up to date information that this weather station retrieves. 



So imagine the weather station got new information once every hour



Our first observer will be the current display 



The second observer will be in charge of forcasting 



In the observer pattern, we have something called a subscription (the **obsevers** need to register for a **subscription** for the **subject**)



The registration goes from the observer to the subject. Whenever something changes in the subject, the subject will broadcast a message to all of its observers. 



New data gets populated into the weather station and the subject will broadcast a message to all of its observers. 



We can handle this in many ways. We could have an update in the Current Display which gets called by the subject. 

That update function, you have a handler that does whatever it needs to do when the data changes.



In the case of the CurrentDisplay, we could set a local variable. In the Forecasting Display, we could set a list of all the historical things.



Recap: One subject and mulitple observers (fan out)



#### Why do we use observer pattern?

If the observers were responsible for getting the data from the subject, they would have to constantly **poll** the **observer** to ask (Did anything change? Did anything change? ...  This would not be effecient)

The number of observers would ultimately multiply the number of polling required. 

#### The solution

We do the opposite. 

All we have is one update ocurring, and that's getting pushed to all the observers. 

-   allows for **loose coupling** (allows systems to operate independently) - the subjects **doesn't have to know** about the observers
-   great for testability when you're only testing one component

#### Class Diagram Example

![](https://hosting.photobucket.com/images/i/jhuntcd/observer.png)

Let's define an interface called Subject (the thing that broadcasts the messages out)

(interface) The Subject's methods: 

-   register() - add's an observer
-   remove() - removes an observer
-   notify() - broadcasts a message to all the observers



Next, let's createa **concrete class** called WeatherStation. The WeatherStation will implement the Subject interface. It will define the three methods above (register, remove, notify) 



Next we need a separate inteface to represent the observers. 

We will call this interface Observer 

(interface) Observer's methods

-   update()



The observers will implement the update method because that's what's going to tell the weather station what it should do with the observer when a change event happens. 



The Subject:

-   WeatherStation
    -   temp
    -   humidty 



Our Observers:

-   CurrentConditions (implements Observer)
    -   temp
    -   humidy
    -   getCurrent()
-   ForecastConditions (implements Observer)
    -   lastSevenDays()



**Recap**:

We have a WeatherStation that is our Subject. We register the current conditions concrete classes which are of interface observer type. Whenever there is an update the temp and humidity, let's propogate that update into the observer classes by calling the update method. 



#### Code Example:

```java
interface Subject {
    public void registerObserver(Observer o); // takes in an observer
    public void removeObserver(Observer o);
    public void notifyObservers(); // calls the update method for all the observers
}
```



```java
interface Observer {
    public void update(int temp, int humidity); // whenever the update is triggered, here is the new measurement
}
```



```java
class WeatherStation implements Subject {
    private List<Observer> observers;
    private int temp; // keep track of last recorded temp and humidity
    private int humidity;

    public WeatherStation() {
        this.observers = new ArrayList<>();
    }

    @Override
    public void registerObserver(Observer o) {
        observers.add(o);
      // take in the observer being passed and add it to the observer array
    }

    @Override
    public void removeObserver(Observer o) {
        int observerIndex = observers.indexOf(o); //Do I have this observer?
        if (observerIndex >= 0) {
            observers.remove(observerIndex);
        }
    }

    @Override
    public void notifyObservers() {
        observers.forEach(o -> o.update(temp, humidity));
      // taking all of the observers, and for every one, calling the update method with the temperature and the humidity
    }

    public void measurementsChanged(int temp, int humidity) {
      // called on the weather station object. (whenever someone does a recording of that weather station, they will call the weather station's measurementsChanged function, pass in the new temp and huidity, set locally, and then call the notify obserers method, )
        this.temp = temp;
        this.humidity = humidity;
        notifyObservers();
    }
}
```



```java
class ForecastDisplay implements Observer {

    private List<Integer> tempHistory;
    private List<Integer> humidityHistory;

    public ForecastDisplay(Subject weatherStation) {
        tempHistory = new ArrayList<>();
        humidityHistory = new ArrayList<>();
        weatherStation.registerObserver(this); // subscribe to the Subject
    }

    @Override
    public void update(int temp, int humidity) {
        this.tempHistory.add(temp);
        this.humidityHistory.add(temp);
        display7DayHistory();
    }

    public void display7DayHistory() {
        //Print Last 7 days History of Temperature and Humidity
        System.out.println("Temperature History: " +
                tempHistory.subList(Math.max(tempHistory.size() - 7, 0), tempHistory.size()));
        System.out.println("Humidity History: " +
                humidityHistory.subList(Math.max(humidityHistory.size() - 7, 0), humidityHistory.size()));

    }
}
```



```java
class CurrentConditionsDisplay implements Observer {

    private int temp;
    private int humidity;

    public CurrentConditionsDisplay(Subject weatherStation) {
      // this referes to this instance of the current conditions display class. We are registering ourselves with the subject
        weatherStation.registerObserver(this);
    }

    @Override
    public void update(int temp, int humidity) {
        this.temp = temp;
        this.humidity = humidity;
        displayCurrent();
    }

    public void displayCurrent() {
        System.out.println("Current Temperature: " + temp);
        System.out.println("Current Humidity: " + humidity);
    }
}
```



```java
public class ObserverPattern {

    public static void main(String[] args) throws InterruptedException {
        //Create the data object (publisher / topic)
        WeatherStation weatherStation = new WeatherStation();

        //Create and register our displays (observers / subscribers)
        CurrentConditionsDisplay currentConditionsDisplay =
                new CurrentConditionsDisplay(weatherStation);
        ForecastDisplay forecastDisplay = new ForecastDisplay(weatherStation);

        //Simulate updates
        for (int i = 0; i < 5; i++) {
            System.out.println("\n--- Update " + i + " ---");

            int randomTemp = getRandomint(-50, 40);
            int randomHumidity = getRandomint(0, 100);

            weatherStation.measurementsChanged(randomTemp, randomHumidity);

            Thread.sleep(1000);
        }
    }

    private static int getRandomint(int min, int max) {
        Random rand = new Random();
        return rand.nextInt(max + 1 - min) + min;
    }
}
```



#### Full Code

```java
package com.example.javalearning.Observer;
import java.util.ArrayList;
import java.util.List;
import java.util.Random;

interface Subject {
    public void registerObserver(Observer o);
    public void removeObserver(Observer o);
    public void notifyObservers();
}

interface Observer {
    public void update(int temp, int humidity);
}

class WeatherStation implements Subject {
    private List<Observer> observers;
    private int temp;
    private int humidity;

    public WeatherStation() {
        this.observers = new ArrayList<>();
    }

    @Override
    public void registerObserver(Observer o) {
        observers.add(o);
    }

    @Override
    public void removeObserver(Observer o) {
        int observerIndex = observers.indexOf(o); //Do I have this observer?
        if (observerIndex >= 0) {
            observers.remove(observerIndex);
        }
    }

    @Override
    public void notifyObservers() {
        observers.forEach(o -> o.update(temp, humidity));
    }

    public void measurementsChanged(int temp, int humidity) {
        this.temp = temp;
        this.humidity = humidity;
        notifyObservers();
    }
}

class ForecastDisplay implements Observer {

    private List<Integer> tempHistory;
    private List<Integer> humidityHistory;

    public ForecastDisplay(Subject weatherStation) {
        tempHistory = new ArrayList<>();
        humidityHistory = new ArrayList<>();
        weatherStation.registerObserver(this);
    }

    @Override
    public void update(int temp, int humidity) {
        this.tempHistory.add(temp);
        this.humidityHistory.add(temp);
        display7DayHistory();
    }

    public void display7DayHistory() {
        //Print Last 7 days History of Temperature and Humidity
        System.out.println("Temperature History: " +
                tempHistory.subList(Math.max(tempHistory.size() - 7, 0), tempHistory.size()));
        System.out.println("Humidity History: " +
                humidityHistory.subList(Math.max(humidityHistory.size() - 7, 0), humidityHistory.size()));

    }
}

class CurrentConditionsDisplay implements Observer {

    private int temp;
    private int humidity;

    public CurrentConditionsDisplay(Subject weatherStation) {
        weatherStation.registerObserver(this);
    }

    @Override
    public void update(int temp, int humidity) {
        this.temp = temp;
        this.humidity = humidity;
        displayCurrent();
    }

    public void displayCurrent() {
        System.out.println("Current Temperature: " + temp);
        System.out.println("Current Humidity: " + humidity);
    }
}



public class ObserverPattern {

    public static void main(String[] args) throws InterruptedException {
        //Create the data object (publisher / topic)
        WeatherStation weatherStation = new WeatherStation();

        //Create and register our displays (observers / subscribers)
        CurrentConditionsDisplay currentConditionsDisplay =
                new CurrentConditionsDisplay(weatherStation);
        ForecastDisplay forecastDisplay = new ForecastDisplay(weatherStation);

        //Simulate updates
        for (int i = 0; i < 5; i++) {
            System.out.println("\n--- Update " + i + " ---");

            int randomTemp = getRandomint(-50, 40);
            int randomHumidity = getRandomint(0, 100);

            weatherStation.measurementsChanged(randomTemp, randomHumidity);

            Thread.sleep(1000);
        }
    }

    private static int getRandomint(int min, int max) {
        Random rand = new Random();
        return rand.nextInt(max + 1 - min) + min;
    }
}
```





#### Code Example of Observer Pattern



## Singleton In Java

A Singleton is a class that can only have one object (an instance of the class). 

The Singleton pattern ensures a class has only one instance and provides a global point of access to it. 

#### Singleton Use

1.   Allows for lazy loading. This means that we can initialize your object creation - only when you need it. We could use a global variable which would be created at the init step up your project. 
2.   When you only need one instance. One example could be a Database Connection. Maybe in some applications you only want one database connection. Restrict databases connections through a class. 
     -   What if you are building a Tesla Car Guidance System - it only makes sense to have one instance of the guidance system initialized at one time because the system could be performing actions on the hardware of the car. Don't want conflicting instructions in a moving car!

#### How it works

Three main things to know about the Singleton pattern.

1.   Create a class with a private constructor. (We are closing the abiliy of external classes to create an instance of this class)

2.   We need a **private static instance** of the class we are using. 

     So if our constructor is private, how do we actually create an instance of the class? 

     We have a factory method that's responsible for creating an instance.

3.   We have a Factory method for creation (a static method for creation)

### Example

```java
private static TeslaCar getInstance() {
  if (teslacar == null) {
    teslacar = new teslacar();
  }
  return teslacar;
}
```

-   teslacar is a class level static variable
-   create a new tesla car instance and return that back if one doesn't exist

#### The Problem With This Code

The multithreading world causes issues here! 

Take the example of two threads 

-   thread 1
-   thread 2

These two threads operate on the same machine and they want an instance of the teslacar. Remember that in the teslacar class, it will be controlling the guidance system, so its super important to only create one instance of the teslacar.. never more than 1!

Let's say the first thread enters our code block from above. 

We create a new TeslaCar instance. 

What happens if we have thread 2 which also calls this method at exactly the same time? 

Both of these threads both think that the instance is null. 

Whichevever thread finishes last will override the teslacar with whatever instance it has created. 

#### The Fix

We could use a sychronized block which ensures that only one thread can enter a piece of code at once so we don't run into this problem.

### The Code

```java
class Teslacar {

    // class level static instance
    private static volatile Teslacar car;

    // private constructor to prevent mulitple instances
    private Teslacar(){}

    // factory method to retreive isntance
    public static Teslacar getInstance(){
        if (car == null){
            car = new Teslacar();
        }
        return car;
    }
}

// main method
public class Singleton {
    public static void main(String[] args){
        Teslacar car1 = Teslacar.getInstance();
        Teslacar car2 = Teslacar.getInstance();

        System.out.println(car1);
        System.out.println(car2);
    }
}
```

-   the private static instance of the Teslacar class called car
-   create a private constructor of the Teslacar type that does nothing (prevent external callers from creating an instance UNLESS they are using our factory method)
-   Factory method - check to see if the car is null (Is this the first time entering this block?)
    -   taking care of multithreading with synchronized keyword
    -   create a new instance of the Teslacar and assign it to car!

#### Summary Singleton

If you take look in the console, you'll see the same instance of the Teslacar object. 

-   we know we created the Singleton correctly!

Singleton - We ensured that a class only has once instance and provided a global point of access to it. 

## Builder

## Facade

## Iterator

# Algorithms and Big O

#### Array2D

#### Brute-Force String Search

#### Quick Sort

#### Palindrome

# Concurrency

#### AsyncAwait

# Error Handling

#### Try Catch

#### Unit Testing

# Decision Making

-   DAAS
-   

## Composition and Inheritance

→ HAS A (Composition)

IS A -> (Inheritance)

<img src="https://miro.medium.com/max/749/0*J_Dm57bKTppN51oZ.png" style="zoom:50%;" />

Subclasses are responsible for implementing their own behavior 

inherits or implements in terms of interface

