# Precourse Java

Once we begin to understand a programming language and what it offers us as developers, we also need to understand the big picture regarding development in practice and building applications at scale. 

With mobile development in both iOS and Android, you will encounter many of the same challenges and problems for developing either type of application. 

As a part of the precourse work, we talk about high level concepts that extend past iOS development. Even more, these same ideas extend past Android mobile development and apply to all levels of computer programming. As you hit landmarks in your learning regarding mobile development, having the foundational knowledge will make learning more applicable and useful. 

As developers, we will be covering the following questions as it applies to iOS and Android development, but more importantly, how it applies to developers as a whole. 

#### What are we building?

Full Stack Applications utilizing modern technologies 

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

    

# Programming Paradigms

#### Object Oriented Programming

We aim to be **full stack developers** who keep our code modular and organized. One of the ways we can achieve this is by using OOP, or Object Oriented Programming design (programming architecture built upon the concept of classes and objects)

#### Procedural Programming

#### Functional Programming

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

#### Delegation

#### Decorator

#### Observer-Observable

#### Builder

#### Facade

#### Iterator

# Algorithms and Big O

#### Array2D

#### Quick Sort

# Concurrency

#### AsyncAwait

# Error Handling

#### Unit Testing

# Decisi

on Making

-   DAAS
-   