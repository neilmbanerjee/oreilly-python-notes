# A Python Q&A Session

# Why do people use Python?

## Software Quality

* Designed to be readable, reusable, maintainable
* Software reuse mechanisms (OO, functional)
* Simple and readable syntax
* "Coherent": everything follows from small set of core concepts 

**Python Philosophy:**
* Explicit is better than implicit
* Simple is better than complex

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

 * 
