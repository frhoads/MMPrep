Challenge 3: Get Your Hands Dirty
=================================
Next up, find the Lynda.com video series entitled: “Objective-C Essential
Training”. Watch each video in the following list and answer the corresponding
question.

Section 1: Getting Started
==========================
[1.1] Installing the tools (4:42)
---------------------------------
You should already have Xcode installed, but you will need to register as an
Apple Developer.

Do you like cats?

**ANSWER HERE**
They're ok I guess.

[1.2] Creating your first application (11:28)
---------------------------------------------
Create your first application using the same steps Simon describes in the video.
Familiarize yourself with the Xcode environment, specifically notice how it can
be manipulated to display different helper tools and how it will attempt to fill
in your code as you type it.

**DO YOU PROMISE YOU DID IT?**
Absolutley

[1.3] Updates to this course (3:31)
-----------------------------------
Why do you think it's important to be aware of the idiosyncracies with older
versions of Objective-C and to keep up with new features as they are added?

**ANSWER HERE, IF YOU DARE…**
It is important to be aware of variations because you will see those variations in older code. Also, new versions have feature enhancements and updates that are valuable for coders.

Section 2: Objective-C Basics
=============================
[2.1] The Objective-C language (4:11)
-------------------------------------
How did Objective-C become the language to learn if you want to make apps for
the iPhone and iPad?

**ANSWER HERE**
Objective-C became that language because Apple purchased NextStep which modernized the C language into Objective-C. Apple then used Objective-C as the basis for Mac OS X and later for iOS.

[2.2] The structure of an Objective-C program (6:15)
----------------------------------------------------
Create a new project. Go to the menu option `Xcode`, `Preferences`,
`Text Editing` and make sure *Line Numbers* is checked in the section marked
"Show." Then add comments describing the purpose of each auto-generated line in
the main.m file. For example on Line 17 I would write: 

```
NSLog(@"Hello, World!");  // instructs the console to output: Hello, World!
```

[2.3] Compiling and running your code (8:37)
--------------------------------------------
Why might you build in one version of iOS but deploy in an older version?

**ANSWER HERE**
You might want to build for the newest version of iOS because for testing purposes but deploy in older versions so customers on older hardware can still run your application.



Section 3: Program Flow
=======================
[3.1] Logging messages to the command line (6:07)
-------------------------------------------------
Following the example in the video, write a program that calculates and outputs
to the console the number of seconds in ten years. Copy and paste your code
here.

**PASTE HERE**
int minutes = 60;
int hours = 24;
int days = 365;

int minutesInTenYears = minutes * hours * days * 10;
   
NSLog(@"there are %i minutes in ten 365 day years.", minutesInTenYears);

[3.2] Writing conditional code (7:01)
-------------------------------------
Using Objective-C, create an integer variable called "day" that represents the
days of the week. Write an if statement that checks whether "day" is a weekend
day. If the day is a weekend day then have your program print a message saying
"Have a nice weekend!" and if it's not, print a message saying "I hope you're
having a good week!"

**PASTE HERE**
 // Saturday and sunday are 7 and 1 respectively, all other days are weekdays.
        int day = 5;
        if (day == 1 || day == 7) {
            NSLog(@"Have a nice weekend!");
        }else{
            if (day == 2 || day == 3 || day == 4 || day == 5 || day == 6) {
                NSLog(@"I hope you're having a good week!");
            } else {
                NSLog(@"That's not a day!");
            }
        }
    }
    
    return 0;
}


[3.3] The switch statement (5:58)
---------------------------------
Create a variable called "hurricaneCategory" and a switch statement that prints
out a message describing a hurricane's category from 1-5.

**PASTE HERE**
{
    int hurricaneCategory = 3;
    
    switch (hurricaneCategory) {
        case 1:
            NSLog(@"It's a category 1 hurricane!");
            break;
        case 2:
            NSLog(@"It's a category 2 hurricane!");
            break;
        case 3:
            NSLog(@"It's a category 3 hurricane!");
            break;
        case 4:
            NSLog(@"It's a category 4 hurricane!");
            break;
        case 5:
            NSLog(@"It's a category 5 hurricane!");
            break;
        default:
	  NSLog(@“I don’t know what type of hurricane this is!”);
            break;
    }
}

@end


[3.4] Code snippets (5:15)
--------------------------
Grab a code snippet, indent it to match the indent of your project, then add
comments to it, then select the entire snippet you just modified and save it as
your own code snippet. Time yourself and record how many seconds it takes you to
do all this.

**IT TOOK ME [] SECONDS**
IT TOOK ME [57] SECONDS

[3.5] Operators and expressions (11:08)
---------------------------------------
List the 6 types of operators described in this video. Provide their name, a
description of their meaning, and the syntax you would use to execute them. What
code snippet does the ternary operator replace?

**ANSWER HERE**
3.5 Arithmetic operators include basic arithmetic symbols “+, *, -, /“ and work just like you would expect them too, including order of operations.

Comparison operators include “==, !=, >, <,” etc. used to make comparison between two items, and return a”true or false” type of evaluation.

Logical and/or operators are used to compare two different expressions and is expressed by “&&” and or is expressed by “||” used like:

    if (a = 5 && b = 2); //if a = 4 AND b = 2
    
    // or
    
    if (c = 4 || d = 6); //if c = 4 OR d = 6


Modulus operator “%” gives us only the remainder when we divide; only used on integers.

Increment or decrement allows us to increase (+=, ++) or decrease  (—=,  — —) and the way the operator is used (either in prefix or postfix) can change the way the variable is increments or decremented.


Ternary operator is expressed as (some condition) ? (True) : (False) so if the condition is true then it will return the value before the colon and if the condition is false it will return the value after the colon. This operator can be used to replace some if/else statements.

[3.6] Loops (8:53)
------------------
Think of a scenario while using a mobile app that might require you to use a
"continue" statement in the middle of a loop.

**ANSWER HERE**
A mobile app a filter is being applied to every photo in the user library except for every third photo or every photo that a user selects. So the continue would skip over a photo that a user selects and apply the filter to the next photo.

[3.7] Functions (10:16)
-----------------------
What is a function? What is a function prototype? What are the purposes of each?
What are the rules for when and how you can call a function?

**ANSWER HERE**
A function chunk of code that is given a name, this makes it easy to reuse. We can pass in parameters if necessary and we can also declare a return type if necessary. A function prototype is a description that the function exists, what it accepts and returns. The description of the functions still needs to exist somewhere, but this allows you to organize your code more neatly.


Section 4: Variables
====================
[4.1] Data types (7:06)
-----------------------
What are the primitive data types in Objective-C? Why did Apple add a set of
classes to handle other data types?

**ANSWER HERE**
The primitive data type in Objective-c are int, float, double, char and BOOL. Apple added classes of other data types to objective-c to make using dates and stings easier, because they are not included in C.

[4.2] Working with numbers (9:33)
---------------------------------
Make a table of Objective-C primitive data types. Add numeric data types and
their properties to this table.

**PRETTY TABLE GOES HERE**
int			Holds a 32 bit integer from -2,147,483,648 to 2,147483,647
float		allows use of non-integers and uses 4 bytes
double		same as float, but uses double precision and takes up 8 bytes
long		compiling for 32 bit has the exact same range, compiling for 64 bit uses  an 8 byte integer
long long	uses an 8 byte integer for both 32 and 64 bit compiling
short		uses a 2 byte integer 
unsigned	a modifier using unsigned makes a non-negative integer, extending the possible positive range
char		a single character in the ASCII set
BOOL		Has only two possible states a “yes” or “no” or “0” and “1”
[4.3] Working with characters (4:39)
------------------------------------
Add char and BOOL (the character data types) to your table created above.

**ANSWER ABOVE!**

[4.4] Variable scope (8:06)
---------------------------
Describe in your own words what the scope of a variable is in Objective-C

**ANSWER HERE**
Variable scope describes where variables can interact with code. The rule of thumb is that variables can work inside deeper leaves of braces but not outside. Global variables can be created that work everywhere in your code.


[4.5] Enumerations (3:35)
-------------------------
What does the `enum` keyword allow you to do?

**ANSWER HERE**
Enumerations allow you to limit the value of a data type and allows have your own specific names for those values.

[4.6] Using typedef (2:17)
--------------------------
When would you define your own data type versus using an enum?

**ANSWER HERE**
One possible benefit of defining your own data type would be that if you need to use it multiple times, that way you can easily describe your own data type and use it as needed.

[4.7] Preprocessor directives (5:56)
------------------------------------
Describe the three common preprocessor directives, `#import`, `#define`, and
`#if DEBUG`. Come up with one example where you would use each.

**ANSWER HERE**
The #import allows you to import files or libraries that lets you do different things. An example of this would be importing image files for the code to use etc.

The #define allows you to define a constant that can be used anywhere in the code. It’s like a “find and replace.” This would be used for any constant that you need to use, say an interest rate, that you can then apply thought your code.

The #if DEBUG is used for if you are running in debug mode. The code will execute between the #if DEBUG and #endif .This is useful so you do not need to remove code between debug and release modes for testing.

[4.8] Working with strings (7:52)
---------------------------------
Define the same string using both NSString and C-style string syntax. Describe
the purpose behind each part of your definition.

**ANSWER HERE**
Objective-C string: NSString *greeting = @"Hello";
greeting is a pointer to the sting, and does not hold the string itself. The string is an object.

C style string: "Hello";


Section 5: Classes
==================
[5.1] Introduction to object orientation (7:36)
-----------------------------------------------
Create an encapsulated (including generalized attributes and behavior)
description of a `MobileMakersParticipant` class. Instantiate a single object
representing yourself as a member of this class.

**DO YOU PROMISE YOU DID IT?**
Yes

[5.2] Using objects and pointers (6:38)
---------------------------------------
What is the pointer’s role in instantiating an object from a class? How is a
pointer different than a primitive?

**ANSWER HERE**
A pointer is used all objects in Objective-c, to create an object, you must use a pointer. Pointers are different than other primitives because that value is not held my the pointer itself, it is just an address to where the information is located.

[5.3] Messages and methods (6:44)
---------------------------------
What is the main difference between Objective-C’s messages and method calls in
other languages? How can this difference be seen as an advantage while
programming?

**ANSWER HERE**
The few differences between calling methods in objective-c are we use square brackets instead of a “.” call, also Method names in objective-c are very long because arguments are not spa rated by a comma, but part of the method name itself. This makes for arguments that are more easily read.

[5.4] Using existing classes in the foundation framework (8:40)
---------------------------------------------------------------
What's the difference between a class method and an instance method?

**ANSWER HERE**
The difference between a class method and an instance method is an instance method acts on an object, like a string, while the class method acts on the whole class.

Try typing "NSD..." into your code window. Use the autofill feature and select a
single class name that starts with those three letters. Once the name has been
auto-completed, use the handy shortcut (Option + click) and investigate the
class whose name just got printed to the screen. Examine the task list for this
class. Do this a few more times until you're familiar with the process, or until
you've exhausted your curiosity, whichever comes last.


Section 6: Memory Management
============================
[6.1] What's new with memory management? (1:45)
-----------------------------------------------
Let it soak in. No questions for this one.

**PHEW**

[6.2] Memory management in Objective-C (6:58)
---------------------------------------------
What is the relationship between a pointer to an object, a block of memory, and
the owning and releasing process. Can you come up with an analogy for this
relationship?

**ANSWER HERE**
You create an object by using a pointer and an area of memory is claimed for that object. So you have a pointer to an area of memory. Then you no longer need the object you issue a call to release the object. Owning an object is something that you create copy or retain, and you must eventually release it, if you didn't not do any of those things, you must not real ease the object.

A simple analogy might be the object is a house, and a pointer is a mailing address for that house, while the block of memory is the plot of land on which the house is built. So when you instantiate an object you build a house on a plot of land and give it an address, when you release the object you clear the house from the plot and allow the plot to be used for other future houses.

[6.3] Object creation (7:31)
----------------------------
What does the new method do when used to create an object instance of a class?
Why do we avoid using this method? How long is an object's lifetime?

**ANSWER HERE**
The new method is a way to allocate an initialize an object at the same time. We do not use this because we will call the class method alloc and than the instance method init, we will sometimes want to initialize with certian variables.

The object last until it is released from memory.

[6.4] Using autorelease pools (5:14)
------------------------------------
How does the autorelease pool work? How and when can you use it deliberately?

**ANSWER HERE**
Autorelease pool allows you to release objects you created later in the future. One way autorelease properly would pair it with method that creates and reruns an object; you don’t know when, or for how long that object will be created, but you do know that it will eventually need to be released, this is when you use autorelease pool.

[6.5] Apple autoreleased objects (3:39)
---------------------------------------
What does ARC stand for? Why is it important to remember this?

**ANSWER HERE**
ARC is an acronym that stands for new alloc retain copy, this is a help acronym that reminds you that any objects you create that has those methods you need to release.

[6.6] Introduction to Automatic Reference Counting (ARC) (4:43)
---------------------------------------------------------------
What does ARC save us from having to do? How does it keep us from having to make
this extra effort?

**ANSWER HERE**
ARC keeps us from having to code in the release of the objects we create. ARC automatically scans our code and determines when to release those objects for us, so we can spend more time building and less time making sure we released an object at the proper time.

[6.7] What ARC manages (2:42)
-----------------------------
What are the differences between ARC and garbage collection? What makes these
differences advantageous?

**ANSWER HERE**
Garbage collection is done at run time and is nondeterministic, which means you do not have control over when the garbage collector runs, this can cause slowdown in the program, ARC is done at the time of the compile with no change to how the program preforms.

[6.8] The rules of ARC (4:20)
-----------------------------
Why can you not release or dealloc memory when working with ARC?

**ANSWER HERE**
You cannot use dealloc because that is part of manual reference counting where you manually deallocate an object when it’s destroyed. Release is also not used because ARC does the reference counting for us and using release would be part of manual memory allocation.


Section 7: Custom Classes
=========================
[7.1] Creating your own classes (14:01)
---------------------------------------
What are the two different sections used to create a class? What do they hold
and what files are they placed in?

**ANSWER HERE**
The two sections created are a .h file and a .m file. The .h file is the header and where you declare the attributes and behaviors for the class. The .m file is where you actually define these behaviors.    

**Challenge!** Create a Tweet class for a twitter style app.
@interface Tweet : NSObject

@property NSString *handle;
@property NSDate *timeStamp;

[7.2] Defining methods (8:36)
-----------------------------
**Challenge!** Define what should get passed in and what should get returned by
each of your methods in your Tweet class above.
-(NSString *) postTweet: (NSString *) input withHandle: (NSString *) handle andTimeStamp: (NSDate *) timeStamp;

**DO YOU LIKE TWITTER?**
I never use it.

[7.3] Defining properties (7:21)
--------------------------------
How did Objective-C programmers handle instance variables before 2012? How are
they handled now? What got easier and what got obscured?

**ANSWER HERE**
Prior to 2012 programmers need to add getter and setter methods to their properties, now using @property does this automatically for you as well as synthesizing the property in the .h and implementation in the .m. This is much easier now than it was previously, however much code is being written behind the scenes to make this happen so the process is being obscured on what is actually happening.

[7.4] Defining initializers (12:30)
-----------------------------------
What are initializers and why do we need to use them? Describe a situations when
you can rely on the standard `init` method and when you have to create your own
custom initializer.

**ANSWER HERE**
Initializers are a way to start methods with some information whether it be an int, float, or an object. You would rely on the standard init method when you have no value to pass to the method. You would create a custom init when you need to initialize with some value, say the default starting score is 100 for a game.

[7.5] Using dealloc (5:33)
--------------------------
Why can we have a dealloc method in a class when using ARC, but we can't call
dealloc manually oursevles when using ARC?

**ANSWER HERE**
We can write a custom dealloc method but we can’t call it because ARC does that for us.

Section 8: Collections
======================
[8.1] Working with C-style arrays (7:12)
----------------------------------------
What are the three constraints when using C-style arrays? Create a C-style array
that holds the days of the week.

**ANSWER HERE**
There are three restrictions when using C-style arrays:
1) There is no bounds checking, meaning the compiler does not check to see if you are using the variable correctly in terms of what it holds.

2) The number of items you have in your array is fix, you can’t change it later.

3) Can’t mix types, you can’t mix a char, with an int, or float, etc.

NSString *daysOfTheWeek [7] = {@"Monday", @"Tuesday", @"Wednesday", @"Thursday", @"Friday", @"Saturday", @"Sunday"};

[8.2] Working with Objective-C array objects (8:00)
---------------------------------------------------
What is the difference between a mutable and an immutable array?

**ANSWER HERE**
The difference between an immutable array and a mutable array is that an immutable array is fix, items can not be added or taken away, while a mutable array can.

**Challenge!**
Create an immutable array containing the days of the week. Create a mutable
array that contains the days of the week that you will be at Mobile Makers. Add
the days of the week from the immutable array to the mutable array.

NSArray *daysOfTheWeek = [NSArray arrayWithObjects: @"Monday", @"Tuesday", @"Wednesday", @"Thursday", @"Friday", @"Saturday", @"Sunday", nil];
        
        
        NSMutableArray *daysAtMobileMakers = [NSMutableArray arrayWithObjects:@"Monday", @"Tuesday", @"Wednesday", @"Thursday", nil];
     
        
        [daysAtMobileMakers addObject: [daysOfTheWeek objectAtIndex:4]];
       
        [daysAtMobileMakers addObject: [daysOfTheWeek objectAtIndex:5]];
        
        [daysAtMobileMakers addObject: [daysOfTheWeek objectAtIndex:6]];
        
        [daysAtMobileMakers addObject: [daysOfTheWeek objectAtIndex:7]];
		 

[8.3] Using dictionaries (5:55)
-------------------------------
Create a dictionary that lists five or more events in your life and the
accompanying year (or date if you want to get fancy) of the event.

**MAKE IT SO**
NSDictionary *lifeEvents =
       [NSDictionary dictionaryWithObjectsAndKeys:
        @"was Born",@"1985",
        @"Moved to Texas",@"1993",
        @"Graduated Highschool",@"2004",
        @"Graduated College",@"2008",
        @"Started Mobile Makers",@"2014",
        nil];

[8.4] Fast enumeration (3:27)
-----------------------------
Use fast enumeration to log the timeline of the life events you described above
to the console.

**AYE AYE CAPTAIN**
for (NSString *year in lifeEvents) {
            NSLog(@"%@ is the year I %@", year, [lifeEvents objectForKey:year]);

Section 9: File Management
==========================
[9.1] Introduction to file management in Objective-C (6:44)
-----------------------------------------------------------
What can you do with files using the methods you are aware of that are available
in Objective C’s Foundation class?

**ANSWER HERE**
Rename a file, move or copy a file, and get attributes.

[9.2] Working with paths and URLs (7:17)
----------------------------------------
What are the three parts of a URL? What are the advantages to using NSURL?

**ANSWER HERE**
The three parts to a URL are the scheme, the domain and the path. Advantages of using NSURL are faster than string paths, they are better for catching errors the URL must be well formed or else it won’t be created. lastly there are more and more classes that will only work with URL.

[9.3] Reading and writing strings (4:38)
----------------------------------------
What would be a reason you would want to write a string to disk instead of just
keeping it memory?

**ANSWER HERE**
You might want to write a string to the dick because you want to save the contents of that string for later use after the program is closed, or so another program could use it later.

[9.4] Archiving objects (12:41)
-------------------------------
Why would you want to archive an object instead of writing the data to disk
using the techniques discussed previously?

**ANSWER HERE**
If you have an object with information, it is more difficult to break apart that object and save them all as separate strings. Using NSKeyedArchiver, it is much easier to save the information of that object to retrieve it later.


Section 10 - More Complex Classes
=================================
[10.1] Inheritance and NSObject (8:13)
--------------------------------------
How can you determine what methods you're inheriting from a super class? How do
you overide a method inherited from a super class?

**ANSWER HERE**
All methods inherit from the superclass NSObject, unless you override them. You can override a method from a superclass by write your own method in your class with the same signature of the method you want to override. 

[10.2] Extending classes with categories (6:31)
-----------------------------------------------
What is the difference between a category and an inheritance? What are the
limitations of using a category?

**ANSWER HERE**
With a category you are not subclassing an existing class, you are adding methods to one. Some limitations are that you cannot add new instance variables using categories.

[10.3] Defining protocols (5:14)
--------------------------------
How are protocols useful?

**ANSWER HERE**
Protocols are useful because they don’t care what thew object is, as long as it conforms to the protocol. This is useful because you can have many different types of object work with a protocol, as long as it conforms.

[10.4] Dynamic typing (11:33)
-----------------------------
What are the advantages and disadvantages to dynamic typing?

**ANSWER HERE**
The advantages of dynamic typing is that if you do not know the object that is getting based in you can use “id” to hold that object. The disadvantages are the compiler can’t check for you if you’ve made a logical error.
