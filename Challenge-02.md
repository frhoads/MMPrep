From the Lynda.com video series “Foundations of Programming: Object-Oriented
Design”, watch each (short) video and answer the correlating questions:


Section 0: Introduction
=======================
[0.1] What to expect from this course (3:06)
--------------------------------------------
What is the intended purpose and potential advantage of learning object oriented
design?

**ANSWER HERE**
Building better, faster and more complex applications more quickly, and with less bugs.

[0.2] Exploring object-oriented analysis, design, and development (1:41)
------------------------------------------------------------------------
Why might it be advantageous to analyze and design before beginning programming?

**ANSWER HERE**
To save time and to think about a project beforehand. This can prevent potential pitfalls and wasted effort on code that must be scrapped.

[0.3] Reviewing software development methodologies (4:08)
---------------------------------------------------------
What is the difference between a "waterfall" and an "agile" approach to
development? What is an iteration and how do we to use them to build software?

**ANSWER HERE**
The “waterfall” approach is a step by step process where once one step is complete, you move on to the next. There is no reversal or revaluation, which is unlike an agile approach, which uses these methodologies. 

Iterations can be inaccurate or incomplete, they just need to be “good enough.” You cycle though manny iterations each including analysis, design and programming.  This is useful for tackling problems in code or design.

Section 1: Core Concepts
========================
[1.1] Why we use object-orientation (2:42)
------------------------------------------
What are the various types of programming languages and in which domain is each
used?

**ANSWER HERE**
Object oriented languages are primarily used in the functional world to build apps. Procedural languages are written as one long procedure, one long piece of code, primarily used on mainframes and is mostly obsolete. There are functional programing languages, and logic programing languages as well, but they do not see much use outside of very specialized purposes and academia. 

[1.2] What is an object? (5:22)
-------------------------------
Describe in your own words the three properties of a computing object.

**ANSWER HERE**
An object has an identity, attribute and behavior. A computing object has an identity that is separate from other computing objects; there are attributes about the object that help us define it and the behavior of the object itself- what it does.

[1.3] What is a class? (4:43)
-----------------------------
Explain how classes are analogous to blueprints. Include the relationship
between a class and an object. Can you think of how the analogy breaks down?

**ANSWER HERE**
First, one must create a class before objects can be made, in the same way that blueprint of a house is used to construct a house, though it is not the house itself.

A class describes a specific instance of an object. A class is a grouping of objects of certain attributes.

[1.4] What is abstraction? (2:45)
---------------------------------
When a developer uses the term “abstraction” what are they describing?

**ANSWER HERE**
They are describing the essential qualities of a class. Instead of focusing on specific attributes, generalize and abstract the common qualities that all objects in a class will share that are important.

[1.5] What is encapsulation? (3:45)
-----------------------------------
What does encapsulation prevent? What does it enable?

**ANSWER HERE**
Encapsulation enables us to restrict access to an object thereby reducing dependencies in the application and making the application easier to debug. It enables information hiding.

[1.6] What is inheritance? (3:35)
---------------------------------
Describe the inheritance relationship between classes. When would this
relationship be advantageous to establish?

**ANSWER HERE**
An inherited class gets all of the attributes of its parent class in addition to new attributes specific to the inherited class. One way this is advantageous is that changes made to the parent class are automatically updated in the inherited class.

[1.7] What is polymorphism? (3:22)
----------------------------------
What is the basic idea behind polymorphism? How can it make the classes we
create more flexible?

**ANSWER HERE**
Polymorphism allows us to be flexible with our classes. Meaning, that called methods will function properly among all related classes despise the class slight differences.


Section 2: Object-Oriented Analysis and Design
==============================================
[2.1] Understanding the object-oriented analysis and design processes (4:13)
----------------------------------------------------------------------------
What are the steps of analysis that come before writing code for an application?
Why do you think these steps make writing the code easier?

**ANSWER HERE**
The first step is to gather requirements this is where you get specific about what the app is going to do. The seconds is Describe the app, build a simple narrative about how people use the app. The third step is Identify the main objects, picking out the most important things that could later become classes. The fourth step is to describe the interactions, between objects. The final step is to create a class diagram, a visual representation of the classes.

These steps make writing code easier because it is an outline for your app. You will spend less time back tracking and rewriting code because you did not think though your class and objects the first time.

[2.2] Defining requirements (6:09)
----------------------------------
What should you have after you've completed the first phase of defining your
requirements?

**ANSWER HERE**
Basically something written down addressing functional and non-functional requirements of the program.This can be done informally or using a methodology like FURPS or FURPS+. The list does not need to be exhaustive, the idea is that you will return to the list later to add and remove items.

[2.3] Introduction to the Unified Modeling Language (UML) (1:54)
----------------------------------------------------------------
What is UML? Why Is it useful to visualize your application before coding it?

**ANSWER HERE**
UML stands for Unified Modeling Language. It is a graphical way of describing relationships in an object oriented system. It is useful to see and sketch out a design of your program before you commit to writing code.

Section 3: Utilizing Use Cases
==============================
[3.1] Understanding use cases (6:11)
------------------------------------
Write a use case for creating an event on your phone's calendar.

**ANSWER HERE**
Title: Create new calendar event
Actor: User

Scenario: User enters in a title for an event. User then selects from an “all-day” event or inputs the start and end times of the event. The User confirms information is correct and the event is created. 

[3.2] Identifying the actors (4:16)
-----------------------------------
Can you think of a use case for a mobile application in which the actor is not
the user of the mobile device?

**ANSWER HERE**
A messaging application that alerts the user when the User has received a new message. Or really any type of alert system, such as bank alerts, download complete message a location services reminder, etc.

[3.3] Identifying the scenarios (5:07)
--------------------------------------
Write another use case for a mobile device user interacting with a calendar
application. This time include a couple extensions when crafting your scenario.

**ANSWER HERE**
Title: Create new calendar event
Actor: User

Scenario: User enters in a title for an event, and if necessary a location. User then selects from an “all-day” event or inputs the start and end times of the event. If necessary the User may enter in additional details like scheduling a repeating event, adding invitees, adding an alert for the event and selecting the category of calendar. The User confirms information is correct and the event is created, if not the user cancels and the information entered is deleted. 

[3.4] Diagramming use cases (4:18)
----------------------------------
Do a google image search for "use case diagram." Notice how many variations
there are. What do they all generally have in common?

**ANSWER HERE**
They all seemed to be ordered in the same way- in a two or three column view with actors on the left the system in the middle and secondary actors (if any) on the right. They all use impel sharps and lines to show a flow and relation to one another.

[3.5] Employing user stories (3:43)
-----------------------------------
Write 5 user stories to describe a mobile user interacting with his or her maps
application.

**ANSWER HERE**
As a user I want to search by business name so I can find where the business is located.

As a user I want to orient the map so I can find out which way I’m facing.

As a user I want to be given directions so it’s easier to know how to get to my destination.

As a user I want to move the map around so I can see the surrounding area.

As a user I wan to zoom in on the map so I can see a specific area in more detail.


Section 4: Domain Modeling (Modeling the App)
=============================================
[4.1] Creating a conceptual model (1:59)
----------------------------------------
What’s your favorite color?

**ANSWER HERE**
Green

[4.2] Identifying the classes (2:27)
------------------------------------
Identify the classes in the use case you constructed for a user interacting with
his or her calendar application in chapter 3.

**ANSWER HERE**
User, Event, Location, Time, Invitees, Alert, Category

[4.3] Identifying class relationships (2:38)
--------------------------------------------
Identify the relationships among the classes you found above. Create a
conceptual model where you diagram these relationships and then upload a picture
of your model below.

**ANSWER HERE**

[4.4] Identifying class responsibilities (6:43)
-----------------------------------------------
Identify the responsibilities of the classes you found above. List them here.

**ANSWER HERE**
User- Create Event, Create Category

Event- Set Time, Set Date, Set Location, Set Attendees, set category

[4.5] Using CRC cards (2:49)
----------------------------
If you’d like, try creating CRC cards for the model you made above. There's no
need to respond here, just try it out and see if you like this form of
organization.

**ANSWER HERE… IF YOU LIKE**


Section 5: Creating Classes
===========================
[5.1] Creating class diagrams (6:11)
------------------------------------
Construct Class Diagrams for the classes you imagine exist in a twitter app, a
maps app, a calendar app, or any other app you would like to make. Do you find
that it is easier to come up with the attributes or with the behaviors? Why do
you think that is?

**ANSWER HERE**
I found that it is easier to come up with class attributes  instead of the behaviors. For me, it Is easier to describe a class in terms of what it contains instead of what it does.To describe what the class does you first need to understand how it will interact with other classes/objects.

[5.2] Converting class diagrams to code (4:57)
----------------------------------------------
How might the separation of interface and implementation in Objective-C be an
advantage when working with class diagrams?

**ANSWER HERE**
This could be advantageous when looking through code and declaring methods or “behaviors.” The .h file is where you could quickly see and access all of your methods while the .m files is where you build them.


[5.3] Exploring object lifetime (5:55)
--------------------------------------
What are the constructors and destructors in Objective-C? Why do we use them?

**ANSWER HERE**
Constructors are created in Objective-C by using an “init” method. A Destructor is used destroying objects and releasing resources.

[5.4] Using static or shared members (5:22)
-------------------------------------------
Like the interest rate example in the video, give three additional examples of
data that would be the same for all instances of a class.

**ANSWER HERE**
Daylight hours in a day
Club memebershhip pricing
Tweet Length

Section 6: Inheritance and Composition
======================================
6.1 Identifying inheritance situations (6:49)
---------------------------------------------
Describe in your own words what inheritance is and how it is useful when
constructing classes.

**ANSWER HERE**
Inheritance is a way to pass along attributes and methods from a parent class to a sub class. 

This is useful when constructing classes and some classes share many of the same attributes. A parent class can be created and the shared attributes can be in the parent class.

[6.2] Using inheritance (2:43)
------------------------------
Referring to the apps on your phone, come up with three examples where you
believe methods are being inherited from superclasses and called by subclasses.

**ANSWER HERE**
The superclass method for bring up my phone keyboard might be called by the subclass for a texting app.  A particular app may call a superclass method to get my location. A clock app my call a superclass method to get the time.
