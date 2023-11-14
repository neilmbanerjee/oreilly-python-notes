# A Python Q&A Session

# Why do people use Python?

## Software Quality

* Designed to be readable, reusable, maintainable
* Software reuse mechanisms (OO, functional)
* Simple and readable syntax
* "Coherent": everything follows from small set of core concepts 

**Python Philosophy:**
`import this` gives you the following:
```
The Zen of Python, by Tim Peters
Beautiful is better than ugly.
Explicit is better than implicit.
Simple is better than complex.
Complex is better than complicated.
Flat is better than nested.
Sparse is better than dense.
Readability counts.
Special cases aren't special enough to break the rules.
Although practicality beats purity.
Errors should never pass silently.
Unless explicitly silenced.
In the face of ambiguity, refuse the temptation to guess.
There should be one-- and preferably only one --obvious way to do it.
Although that way may not be obvious at first unless you're Dutch.
Now is better than never.
Although never is often better than *right* now.
If the implementation is hard to explain, it's a bad idea.
If the implementation is easy to explain, it may be a good idea.
Namespaces are one honking great idea -- let's do more of those!
```

## Developer Productivity

* Optimized for speed of development
  * Simple syntax
  * Dynamic typing
  * No compiling or linking
  * Built-in tools
* Python LoC 1/3-1/5 of C, C++, Java

## Program Portability

* Runs the same across major OS

## Support Libraries

* Large standard library
* Extensive third party domain

## Component Integration

* Can integrate with other technologies
  * C and C++
  * Java, .NET, COM, etc

## Enjoyment

* Subjective, but ease of use == fun

# Is Python a "Scripting Language"?

* "Object-oriented scripting language"
  * Blends procedural, functional, object-oriented paradigms

## What does "scripting language" mean? 

* Shell tools: command-line stuff, quick tools
* Control language: "glue layer" connecting other things
* Ease of use: Quickly coding tasks

Answer: Depends on who you ask, and the definition.

# What's the Downside?

## Execution Speed

* Execution is slower than compiled languages... but still pretty fast.
* Python code compiled to byte code, then interpreted.
* Byte code is platform-independent but less efficient than binary code.
* Python interpreter has bits of compiled C code.
* Speed of development gain usually offsets speed of execution loss.
  * Computers are really fast now.

## Other Stuff

* Rate of change: Lots of new stuff being added.
* Batteries included: Sometimes prebuilt stuff changes or breaks.
* Usual open-source crap: Elitism, anarchy, preferences.

# Who Uses Python Today?

* Top 5-10 most used language
* 20+ years old
* Lots of govt agencies, nonprofits, corporations

# What Can I Do with Python?

* Pretty much anything, but it's very commonly used for a few things.

## Systems Programming

* Utilities for processing files, launching other things, etc.
* [POSIX](https://en.wikipedia.org/wiki/POSIX) bindings
  * TLDR: Standard interface for operating systems.
  * Environment variables
  * Files
  * Threads
  * Command-line stuff
 
## GUIs

* Simplicity and fast development
* Various toolkits available
  * Portable: run across different operating systems.

## Internet Scripting

* Standard internet functionality
  * Communicate over sockets
  * Transfer files
  * Parse/generate XML, JSON
  * Email
  * Load & parse web pages
* Lots of third party tools
* Lots of web development frameworks
  * Django is the main one now

## Component Integration

* "Glue language" for controlling other systems and components
  * Use something easy to manage other complex things
* Extend/embed C programs

## Database Programming

* Connects to all the usual DBs
  * Portable database API
  * Built-in SQLite engine
* `pickle`: Save and restore complex data structures.
* ORMs
  * Interact with DB data like it's Python objects
  * SQLAlchemy, PyMongo, etc

## Rapid Prototyping

* Can start something in Python and then move to C
* Common component interface 

## Numeric and Scientific Programming

* `NumPy`: Ease of use plus sophistication and performance.
* Basically you can write code to crunch tons of data with Python
  * Easy to write
  * Runs fast

## And More

TLDR you can do basically anything with Python.

# How is Python Developed and Supported?

* Open source, big community
* PEP: Python Enhancement Proposal

## Open Source Tradeoffs

* Some chaos, some mistakes
* But stable versions tend to be stable

# What are Python's Technical Strengths?

## Object-Oriented and Functional

* Python is OO from the ground up.
  * Class functionality: Polymorphism, overloading, multiple inheritance.
  * Python classes can subclass from other languages (with some glue).
  * But still OO optional - can do a lot without classes.
* Python has functional tools now too
  * Don't worry too much about what this means yet

## It's Free

* Open source, free to use and distribute.
* Well-supported, robust online community.
* Source code is available (if you really want it).
* Pretty conservative to changes.

## It's Portable

* Python runs anywhere.
  * Pretty much the same code should run everywhere.

 ## It's Powerful

Recurring theme: It's easy to use but still can do a lot of stuff.
 * Dynamic typing: Python keeps track of your variable types.
 * Automatic memory management: In some languages you have to do this manually.
 * Programming-in-the-large: Mechanisms to manage complexity in large code bases.
 * Built-in object types: Lists dicts strings etc.
 * Built-in tools: Lots of functionality for those types.
 * Library utilities: Big standard library.
 * Third-party utilities: Lots of people wrote Python tools.

## It's Mixable

* Easy to wire up Python with not-Python

## It's Relatively Easy to Use

* Simpler than C++ Java etc.
* Quick turnaround is really valuable in the real world.

## It's Relatively Easy to Learn

* Again: Simpler than C++ Java etc.
* Again: No compiling, no linking.
* **Important nugget:** Simple enough that "here's some Python, you can modify it as you like" is a reasonable thing to say.

## It's Named After Monty Python

* I did not know this.

# How Does Python Stack Up?

* Again: simpler than C++ Java etc.
* Again: more powerful
* Again: more readable
* Again: more widely used
* It's subjective, but TLDR: Python is at least pretty good at everything.

# Engineering vs Art

* Readability matters.
  * Language influences readability.
* Code is read more often than it's written/updated/deleted.
  * Good code communicates its purpose clearly.
* Confusing to solve the same problem in many different ways.
  * Python pushes you to do things one way.
