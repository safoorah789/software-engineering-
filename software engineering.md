# **Software Engineering**
## Chapter 1 


## **Why modeling of software requirements is beneficial?**


* Modeling software needs and requirements shed light on the wants of users.


* Models significantly enhance communications within and across development teams.
This is so because these models represent requirements in the problem space, designs in the solution space, and constraints in the architectural space. Overall, models provide the project team
with major opportunities to identify gaps, errors in understanding, technology mismatch, and
changing user expectations. Models allow teams to do all they need to do before they start “coding.



* Modeling in software engineering serves two major purposes: to help
shed light on the existing business reality and to create a new business reality. The importance of
modeling in SE is multifunctional: understanding existing systems, applications, and processes,
followed by the creation of new processes, providing a basis for testing and enabling effective communications with all stakeholders.

## **Fundamentals of object oriented programming**

Foundations for techniques and standardization in SE are based on the fundamentals of OO. The
OO fundamentals provide strong theoretical foundations for the analysis, design, architecture,
coding, and testing of software systems. Some core terms of SE are 
* Object
* Data 
* Classes
* Programs



## Programs

Structured code specific to a programming language that reflect an algorithm.Programs are written primarily to
manipulate data according to the logic specified by users.


## Classes

Specific styles of software programs that encapsulate data with functions (methods). Classes are object-oriented in nature. Classes are put together in different ways to produce systems.


## Data

Instance-level representation of the business reality (characteristics) that is encoded
and stored within databases. Relational databases store data as records. Object-oriented databases store data and their functions together. Unstructured data (such as graphics, audio, and descriptive text) require special types of storage.


## Object

Instances of classes that comprise both data and the behavior associated with the data at runtime. Since objects are runtime entities based on the classes that define them, there can be a number of variations to objects for the same class.

### Fundamentals of Software engineering
 
The six fundamentals of object-oriented SE revolve around data and extract value from them in various
ways. Therefore, understanding these object-oriented fundamentals is at the crux of becoming a
good software engineer. These object-oriented fundamentals are as follows:

1. Classification (grouping)
2. Abstraction (representing) 
3. Encapsulation (modularizing)
4. Association (relating) 
5. Inheritance (generalizing) 
6. Polymorphism (executing) 



**Classificaton**
Classification is the starting point of OO. Good software engineers make sense of requirements
by first identifying entities in the business space. Once these entities or potential objects are identified, they are grouped or classified. Classification is based on the requirements appearing in the problem space, and these requirements, in turn, are iteratively modified based on the classification.

**Abstraction**

Objects, which are real-world entities, need to be represented by a template that also defines their
characteristics and behavior. Collections of classified objects are abstracted to classes. A class provides a detailed definition of all objects that can be instantiated from it. This is the basic level of
abstraction

**Encapsulation**
 
  Encapsulation is the fundamental of wrapping chunks of cohesive data with
meaningful code. Encapsulation localizes data and prevents them from being directly exposed
to the rest of the system. Encapsulation enhances quality and reuse because the data are only
accessible through calls to the operations (methods or functions) of a class.

**Association**

Objects are classified and abstracted into classes. Classes don’t exist in isolation. They relate to
other classes in multiple ways. The association relationship is a mechanism for two (more) classes
to relate to each other.

**Inheritance**

Classes in OO also relate to each other through inheritance. Inheritance results from classes being
generalized into higher-level or abstracted classes.A class can inherit the attributes, behavior, and
relationships of another class. Inheritance enables the extensibility of design and reuse of code. 

**PolyMorphism**

Polymorphism is the ability of an instantiated object (at runtime) to understand and interpret the
message sent from a calling object. This interpretation of a message by an object depends on its
own characteristics and definition.

# UML
## What is UML And its purpose?

The UML was first proposed around 1995 as a combination of the three most popular methods (processes) of that time: Booch,17 object modeling technique,18 and Objectory.19 Later, several other methods merged into UML, eventually resulting in the popular UML version 1.4. Around
2004

## UML Usage ?

There are five ways in which the UML is used in SE:


**Visualizing**

This is the primary purpose of the UML as its notations and diagrams provide an industry standard mechanism for pictorial representation of requirements, processes,
solution design, and architecture. These visuals are created using modeling CASE tools,
which also enable team-based sharing of modeling work.

**Sppecifying** 

UML Facilitates specification of modeling artifacts. For example, specifications for actors, use cases, classes, attributes, and operations provide additional details for visual notations. These specifications go a long way toward enhancing the quality of solutions since reviews of specifications help resolve many misunderstandings between the users and the developers.

**Constructing**

UML is used for software construction because it enables code generation (e.g., C++, Java) depending on the CASE tool being used. However, this construction feature of the UML has limited application, mainly because once the code is generated, most practical projects work directly on modifying the code rather than the designs. Round-trip engineering was meant to help modify the designs based on updated code, but this feature
is not as popular in practice as earlier thought.

 **Documenting**
 
 With the help of UML, additional and detailed documentation for requirements, architecture, design, project plans, tests, and prototypes is provided to enhance specifications and visual representations.


**Maintaining**

Good UML models are a significant aid in ongoing maintenance of software systems. Models allow an easy view of an existing system, its architecture, and IT design. This allows programmers to identify the correct places within the system for changes and, more importantly, understand the effect of their changes on the rest of the system.