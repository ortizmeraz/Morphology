---
Title: 			Functional and Object Oriented Analysis and Design An Integrated Methodology
Author:	  Shoval
Year:			2006
Added in:		2021-12-21
tag:			Book
fullref: 		"Shoval, P. (2006). Functional and Object Oriented Analysis and Design : An Integrated Methodology. Idea Group, Inc. http://ebookcentral.proquest.com/lib/concordia-ebooks/detail.action?docID=268984"
status:			Need to review
---
# Functional and Object Oriented Analysis and Design : An Integrated Methodology 
```ad-quote
Shoval, P. (2006). Functional and Object Oriented Analysis and Design : An Integrated Methodology. Idea Group, Inc. http://ebookcentral.proquest.com/lib/concordia-ebooks/detail.action?docID=268984
```
## Concepts
[[object oriented approach]]
[[ object oriented]]
 [[object oriented analysis]]
## Tags
#tag 
#2021-12-21

```ad-info
color: 255, 215, 0
title: summary
icon: book


```
## Bullet points

1. Concepts (P5):
	1. First Definitions 
		1. An **object** is a thing for which data is saved and actions (functions) are performed. An object is an abstraction of something in the real world that we need to represent in the system. An object has attributes which are a collection of data which describe it. An object’s state is the values which its attributes possess in a certain moment. In addition, an object has a behavior; that is, the various functions which can operate on the object. Other common terms for functions are services and methods.
		2. A **class** is a collection of objects of the same kind; that is, an object is an instance of the class to which it belongs. All objects belonging to a specific class have the same attributes and behavior. Classes can be organized in superclass and subclass hierarchies. Inheritance means that a subclass inherits attributes and behavior from its superclass. Multiple-inheritance means that a subclass can inherit from more than one superclass.
	2. **Longer Definitions** 
		- **Class**
			- A class is a collection of objects of the same type, that is, objects having the same attributes, behavior (functions), and types of relationships.
		- **Object** 
			- A class is a collection of objects of the same kind; that is, an object is an instance of the class to which it belongs. All objects belonging to a specific class have the same attributes and behavior. Classes can be organized in superclass and subclass hierarchies. Inheritance means that a subclass inherits attributes and behavior from its superclass. Multiple-inheritance means that a subclass can inherit from more than one superclass.
			- An object is characterized by attributes, which have values. The values of the attributes are the object’s data.
			- In addition to attributes, an object has “behavior,” which means all the actions or functions that can operate on the object or its  attributes during its lifetime in the system.
		- **Attribute**
			- An attribute is a type of data that needs to be stored for every object. As already said, all the objects belonging to the same class have the same attributes. The data, that is, the values of the attributes, are stored within each object (in the system’s database), while the definitions of the attributes (e.g., the attribute names and their data types) are kept separately, as part of the class definition.
			- Attribute names are unique for every class (but not necessarily for the whole schema). An attribute has a data type and length, which determines the type of data it may store.
		- **Relationships** 
			- As we already know, objects are not necessarily “independent,” but can be related to other objects (either in the same class or in other classes). We distinguish between three kinds of relationships: ordinary relationships, aggregations (whole-part relationships), and inheritance (class-subclass relationships).
			- *Ordinary Relationships* (==part to part?==)
				- An ordinary relationship (or association), like a relationship between entities in the ER model, means that an object in a certain class can be related to one or more other objects. 
				- Reference Attributes A relationship between classes is not represented only by a connecting line, but also by defining reference attributes (also called relationship attributes) of the respective classes. A reference attribute is given a name based on the name of the relationship or on the role of its objects in the relationship...
				- In general, for a one-to-one relationship, a referenced attribute is defined in each of the involved classes; for a one-to-many relationship, one for the reference attributes—that of the class which is in the “one” side of the relationship—is a set attribute; for a many-to-many relationship, both reference attributes are sets.
				- Attributes of Relationships. A many-to-many relationship may have attributes. In the objects model, we specify the relationship attribute(s) together with the respective reference attributes. This forms a tuple whose components are the reference attribute and the relationship attribute(s).  The more relationship attributes we have in a many-to-many relationship, the bigger the amount of duplicities. The problem can be avoided by defining a “relationship class” between the M:N related classes.
			-  *Aggregations* (whole-part relationships)
				-  Aggregation is a structural relationship between objects from different classes that “come together.” In most cases we are dealing with a relationship between one object which is the “whole,” and other objects which are its “parts.” That is why aggregation is also called “whole-parts” relationship.
				-  p34
2. (P124) Many of the OO methodologies were aimed mainly for the development of real time or reactive systems. From a modeling point of view the main concern in such systems is to model events which occur in the external environment of the system, and the required system’s response to the events, which also means modeling the possible states of objects in response to events affecting them. Only some of the OO methodologies were aimed mainly for the development of business-oriented (i.e., organizational-managerial) IS. One of the popular early OO methodologies for the development of such systems was OOA/OOD (Coad & Yourdon, 1991, 1991). We use it to demonstrate this type of OO methodology.
**To do [[object oriented analysis]] and [[object oriented design]]**
3. It deals with two phases of development: [[object oriented analysis]|OOA]] deals with system analysis and [[object oriented design|OOD]]—with system design.
	1. **Identifying classes and objects**: This is the main activity at the analysis phase, and from it the other activities are derived. During this activity, all the object classes that exist in reality and need to be included in the system are discovered and defined.
	2. **Identifying structures**: In this activity a distinction between two kinds of structures is made: *generalization-specification* (also termed is-a, or inheritance relationship), and *aggregation* (also termed whole-parts relationship).
	3. **Identification of subjects**: In this activity, which is relevant when dealing with large-scale systems, the *main subjects* of the sought system are identified, and the *various classes are assigned to those subjects*. Every subject includes classes which have relatively many structural relationships among themselves and relatively few structural relationships with classes outside the subject.
	4. **Defining attributes**: In this activity, the attributes of the various classes and the (ordinary) relationships between classes are defined (besides the structures identified earlier).
	5. **Defining services**(==I asume these refer to 'functions==): In this activity, the functions of every class are identified, and their logic is described. Sometimes, a certain service needs the assistance of another service (in the same class or in another one); therefore, message connections are defined between the calling classes (the sender) and the receiving classes.
4. These are the main activities of OOA at the analysis phase. OOA does not prescribe that they must be performed exactly in the aforementioned order, and it is even possible to work on some of them concurrently. Moreover, since system analysis is an iterative process, the same activity may be repeated until a “good” model is obtained. 
5. At the end of this phase, an OO schema consisting of the five following layers is created: **(1) a subject layer**; **(2) an object and classe layer; (3) a structure layer; (4) an attribute layer; and (5) a function (service) layer.** 
6. ** Unified Modeling Language (P127)**
7. *Object management group* (OMG) is a *consortium* of companies and organizations operating in the fields of computers, software, and related areas *whose goal is to standardize methodologies* and techniques for the development of software in the OO approach.
8. By “language” they meant visual techniques and notations that will enable OO developers to describe and define the components of the system being developed from various viewpoints and in various stages of development. The standard was meant to tear down the “Tower of Babylon” of techniques and notations that dominated until then, and to be used as a standard by OMG members.
9. It is important to clarify that UML is not a development methodology. It provides various techniques with graphic notations (diagrams) enabling developers to present software system models in different forms and from different viewpoints, but UML in itself does not dictate which techniques to use in the development of an application or the order in which they should be used.
10. The 12 diagrammatic techniques included in UML can be classified in three categories:
	- **Structure diagrams**: diagrams which deal with the static structure of the system. They describe the system’s components and the relationships between them. There are four types of structure diagrams: class diagram, objects diagram, components diagram, and deployment diagram.
	- **Behavior diagrams**: diagrams which deal with the dynamic, that is, functional aspects of the system. They describe the system’s behavior over time. There are five types of behavior diagrams: use case diagram, sequence diagram, collaboration diagram, state chart, and activity diagram.
	- **Model management diagrams**: diagrams which deal with the management and organization of the system’s components. There are three types of model management diagrams: package, subsystem diagram, and model diagram.
10. **Structure DIagrams | Class Diagram**
11. ![[Pasted image 20211221143219.png]]