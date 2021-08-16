

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

#### What if something goes wrong?

 We need **error handling** to fail – successfully.

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

## Singleton In Java

A singleton is a class that can only have one object (an instance of the class). 

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

## Decorator

Attaches additional responsibilities to an object dynamically. Decorators provide a flexible alternative to subclassing for extending functionality. 

Typically when you want to add additional functionality to a class, you subclass → override some of the functionality of the parent class. 

#### Example

Animal - Superclass

Dog - Subclass 

Speak method on the parent class which you override in the subclass 



The decorator pattern relies on composition instead of inheritance 

Main idea - you can impersonate a class and add additional functionality without any of the users of the class knowing that its different.  

Compute the cost of beverages for a coffee shop.

 (different coffees with options)



Coffee - Cost and Description 



We will impersonate the coffee class using abstract classes. 



## Observer-Observable

One to many - observer

One to one - delegation 

#### Builder

#### Facade

#### Iterator

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

## Strategy Pattern 

defines a family of algorithms and encapsulates each one and makes them interchangable 

So when we are using **OOP**, we wrap a **class** around this functionality, and makes them interchangable.

We could use an **interface** here so that you could swap out these behaviors at any point in time

The strategy let's the algorithm **vary indepndently** from the clients that use it. 



Encapsulate a behavior into a class and make that class **interchangable** with other classes.

So a host class can use it and use those low level **encapsulations** of behaviors **without having to know how they are implemented or how they work**. 



Let's use the example of a duck. Ducks have different **behaviors associated with them**. 

-   All ducks can swim 



What would happen if we wanted to add the ability to fly for the duck?

-   fly()

Not all ducks fly. In this example, only some ducks fly -- Mallard ducks can fly. Other ducks don't fly. 

![Screen Shot 2021-08-15 at 5.20.37 PM](/Users/jameshunt/Desktop/Screen Shot 2021-08-15 at 5.20.37 PM.png)



How do we accomplish this? 



We could add a fly function above. In the subclasses, we could **override** the fly method with something that has no behavior... maybe throw an exception?

But this isn't the best way to do this. This isn't the OOP way. 





So what is the correct way? Take a look at these other class diagrams. 

![Screen Shot 2021-08-15 at 5.20.14 PM](/Users/jameshunt/Desktop/Screen Shot 2021-08-15 at 5.20.14 PM.png)



So we have the Mallard Duck and the Red Duck. 

So a Mallard duck is able to fly. It has the Swim function that it can override or inherit from the parent class.. It also has a fly function. 

But the Red Duck only knows how to swim, it does not know how to fly. 



So how could we code this fly function in an OOP way but maybe by using an interface or something that makes this more extensible?

So the duck would be the **superclass** and Mallard Duck and Red Duck would be the **subclasses**. 



Now we want to add fly functionality. We could create a Flyable interface. And then the Flyable interface would have a fly function, and the Mallard Duck would implement the fly() function.



This would work, and many programmers would go this route! So it makes sense for OOP.



But the problem with this implementation is .. what if we had a different subclass... 

a Grey Duck.



And the Grey Duck also needs to fly. We want the fly function to do the SAME thing that exists in the Mallard Duck.

So then the grey duck would also need to implement the fly function as well. 



That's not very reusable. We want to implement the fly function once, and then have that shared between all of the classes.



This is where the Stragegy pattern comes in!



Recap: We have a duck superclass and we want to implement the fly function for some if its subclasses. A natural way to do this is with an interace with a fly function. For the classes that want to implement flyable interface, they can have their own fly function.



Now any other class that want's the same fly funciton needs to redefine the same fly function used in the other classes.



How do we fix it with the strategy pattern? 



<img src="/Users/jameshunt/Desktop/Screen Shot 2021-08-15 at 5.36.46 PM.png" alt="Screen Shot 2021-08-15 at 5.36.46 PM" style="zoom: 50%;" />

We can fix it by...

We won't bind it to any functionality that is defined at compile time. To make it so that we can take that behavior and encapsulate it .. put it into a class that we can reuse so that we can pass it around later. 



So we do that by using an interface. 



We will create an **interface** called Fly Behavior. So instead of tying the implementation of Fly Behavior into Mallard and Red Duck, we wil pulll that out and put it into an interface.

This Fly Behavior interface will have a **concrete implementation** it can have as many implementations as you want. 



So ducks fly with wings. We could have an implementation of the fly behavior interface being called the FlyWithWings implementation. This Fly With Wings class.. it needs to implement something. 



Let's say that the Fly Behavior had a **function** called fly() that would be implemented by the FlyWithWings class.

Now this FlyWithWings **class** can define **fly()** in any way it wants, and then create an instance of this **FlyWithWings** class, and pass that in to many different Ducks. 



So now instead of recyling that fly function like we saw previously, we can just create that single instance, and pass that to the duck, and allow that to be used by any of the other classes (Host classes).



So what do we need to change to our UML class diagram? 



We need to add an instance level variable of type Fly Behavior in the Duck class. Then we need to add a mechanism to invoke the FlyBehavior fly function. We can do this in many ways. We could create a performFly() Function in the Duck class which would call on the FlyBehavior method. 


Then we could change the constructor of the Duck class to take in a Fly Behavior and pass that in at runtime. We could create a setter so that we could change this functionality later so.. if we had many different types of the fly behavior interface, these could be swapped out at runtime. 



So now, the Mallard Duck when its instantiated, can call the performFly() function, and it will fly. 

And the Red Duck, if we have a different implementing class.... something called NoFly(), this type of duck doesn't fly. 



The Red duck could use the NoFly() Class because it doesn't fly. 



So the benefit is that we can create a single instance of this and just pass it along. 



Now let's use a real coding example!



`Duck.java` - class

```java
public abstract class Duck {
	protected FlyBehavior flyBehavior;
	public Duck(FlyBehavior flyBehavior){this.flyBehavior = flyBehavior}
	public void performFly(){ flyBehavior.fly(); }
}
```

So we have a Duck class (abstract class)

We have an instance level variable called flyBehavior of type FlyBehavior.

We have a constructor that takes in that flyBehavior and sets that variable.

We have a performFly function that simply invokes the flyBehavior's fly function.



 `FlyBehavior.java` - interface

```java
public interface FlyBehavior {
	public void fly();
}
```

the interface has a fly function. 



`FlyWithWings.java` - concrete class

```java
public class FlyWithWings implements FlyBehavior {
	@Override
	public void fly() {System.out.println("I'm Flying");}
}
```

Concrete class implements the FlyBehavior interface

We are ovveriding that FlyBehavior interface by actually implementing it.. printing out "I'm Flying"



`Mallard Duck.java`

```java
public class MallardDuck extends Duck {
	public MallardDuck(FlyBehavior flyBehavior){
		super(flyBehavior);
	}
	public void performFly(){flyBehavior.fly();}
}
```

Mallard Duck is an implemention of that abstract Duck class. 

It uses super to call the base constructor 

Performs fly by calling the flyBehavior's fly function.



If we take a look at the runner of this class... the Main function. What does this look like? 

`Main.java`

```java
public class Main {
	public static void main(String[] args){
		FlyBehavior flyWithWings = new FlyWithWings();
		Duck mallardDuck = new MallardDuck(flyWithWings);
		
		mallardDuck.performFly();
	}
}
```

We instatiate an instance of the Fly Behavior and create a new instance of the mallard duck and passing in flyWithWings.

We only need to define flyWithWings once. 



Remember that these behaviors can be interchanged with any implementing classes of type FlyBehavior.

So we can swap out the behaviors of these ducks at runtime using a setter function. 



Strategy Pattern - Encapsulates behavior in a concrete class and lets you pass it around and resuse it!

​                                                                                                                                                                                                
