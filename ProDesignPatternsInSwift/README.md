# Book
Pro Design Patterns in Swift

# Author
Adam Freeman

# Publishing Year
2015

# Table of Content
Part I: Getting Ready

Chapter 1: Understanding Design Patterns
Putting Design Patterns into Context
Introducing Design Patterns
Understanding the Structure of a Design Pattern
Quantifying the Value of Design Patterns
Using a Design Pattern After the Problem Occurred
Understanding the Limitations of Design Patterns
About This Book
What Do You Need to Know?
What Software Do You Need?
What Is the Structure of This Book?
Where Can You Get the Example Code?
Summary

Chapter 2: Getting Used to Xcode
Working with Xcode Playgrounds
Creating a Playground
Displaying the Value History of a Variable
Using the Value Timeline
Displaying UI Components in a Playground
Working with OS X Command Line Tool Projects
Creating a Command-Line Project
Understanding the Xcode Layout
Adding a New Swift File
Summary

Chapter 3: Creating the SportsStore App
Creating an Unstructured iOS App Project
Creating the Project
Understanding the Xcode Layout
Defining the Data
Creating the Basic Layout
Adding the Basic Components
Configuring Auto Layout
Testing the Basic Layout
Implementing the Total Label
Creating the Reference
Updating the Display
Implementing the Table Cells
Defining the Custom Table Cell and Layout
Setting the Table Cell Layout Constraints
Creating the Table Cell Class and Outlets
Implementing the Data Source Protocol
Registering the Data Source
Testing the Data Source
Handling the Editing Actions
Handling the Events
Testing the SportsStore App
Summary

Part II: The Creation Patterns

Chapter 4: The Object Template Pattern
Preparing the Example Project
Understanding the Problem Addressed by the Pattern
Understanding the Object Template Pattern
Implementing the Object Template Pattern
Understanding the Benefits of the Pattern
The Benefit of Decoupling
The Benefit of Encapsulation
The Benefit of an Evolving Public Presentation
Understanding the Pitfalls of the Pattern
Examples of the Object Template Pattern in Cocoa
Applying the Pattern to the SportsStore App
Preparing the Example Application
Creating the Product Class
Applying the Product Class
Expanding the Summary Display
Summary

Chapter 5: The Prototype Pattern
Understanding the Problem Addressed by the Pattern
Incurring Expensive Initializations
Creating Template Dependencies
Understanding the Prototype Pattern
Implementing the Prototype Pattern
Cloning Reference Types
Understanding Shallow and Deep Copying
Copying Arrays
Understanding the Benefits of the Prototype Pattern
Avoiding Expensive Initializations
Separating Object Creation from Object Use
Understanding the Pitfalls of the Prototype Pattern
Understanding the Deep vs. Shallow Pitfall
Understanding the Exposure Distortion Pitfall
Understanding the Nonstandard Protocol Pitfall
Examples of the Prototype Pattern in Cocoa
Using Cocoa Arrays
Using the NSCopying Property Attribute
Applying the Pattern to the SportsStore App
Preparing the Example Application
Implementing NSCopying in the Product Class
Creating the Logger Class
Logging Changes in the View Controller
Testing the Changes
Summary

Chapter 6: The Singleton Pattern
Preparing the Example Project
Understanding the Problem That the Pattern Solves
Understanding the Shared Resource Encapsulation Problem
Understanding the Singleton Pattern
Implementing the Singleton Pattern
The Quick Singleton Implementation
Creating a Conventional Singleton Implementation
Dealing with Concurrency
Understanding the Pitfalls of the Singleton Pattern
Understanding the Leakage Pitfall
Understanding the Shared Code File Pitfall
Understanding the Concurrency Pitfalls
Examples of the Singleton Pattern in Cocoa
Applying the Pattern to the SportsStore Application
Protecting the Data Array
Protecting the Callback
Defining the Singleton
Summary

Chapter 7: The Object Pool Pattern
Preparing the Example Project
Understanding the Problem That the Pattern Solves
Understanding the Object Pool Pattern
Implementing the Object Pool Pattern
Defining the Pool Class
Consuming the Pool Class
Understanding the Pitfalls of the Object Pool Pattern
Examples of the Object Pool Pattern in Cocoa
Applying the Pattern to the SportsStore Application
Preparing the Example Application
Creating the (Fake) Server
Creating the Object Pool
Applying the Object Pool
Summary

Chapter 8: Object Pool Variations
Preparing the Example Project
Understanding the Object Pool Pattern Variations
Understanding the Object Creation Strategy
Understanding the Object Reuse Strategy
Understanding the Empty Pool Strategy
Understanding the Allocation Strategy
Understanding the Pitfalls of the Pattern Variations
Understanding the Expectation Gap Pitfall
Understanding the Over- and Under-utilization Pitfalls
Examples of the Pattern Variations in Cocoa
Applying a Pattern Variation to SportsStore
Summary

Chapter 9: The Factory Method Pattern
Preparing the Example Project
Understanding the Problem That the Pattern Solves
Understanding the Factory Method Pattern
Implementing the Factory Method Pattern
Defining a Global Factory Method
Using a Base Class
Variations on the Factory Method Pattern
Understanding the Pitfalls of the Pattern
Examples of the Factory Method Pattern in Cocoa
Applying the Pattern to the SportsStore Application
Preparing the Example Application
Implementing the Factory Method Pattern
Consuming the Factory Method Pattern
Summary

Chapter 10: Abstract Factory Pattern
Preparing the Example Project
Understanding the Problem That the Pattern Solves
Understanding the Abstract Factory Pattern
Implementing the Abstract Factory Pattern
Creating the Abstract Factory
Creating the Concrete Factories
Completing the Abstract Factory
Consuming the Abstract Factory Pattern
Variations on the Abstract Factory Pattern
Hiding the Abstract Factory Class
Applying the Singleton Pattern to the Concrete Factories
Applying the Prototype Pattern to the Implementation Classes
Understanding the Pitfalls of the Pattern
Examples of the Pattern in Cocoa
Applying the Pattern to the SportsStore Application
Preparing the Example Application
Defining the Implementation Protocols and Classes
Defining the Abstract and Concrete Factory Classes
Consuming the Factories and Implementation Classes
Summary

Chapter 11: The Builder Pattern
Preparing the Example Project
Understanding the Problems That the Pattern Solves
Understanding the Builder Pattern
Implementing the Builder Pattern
Defining the Builder Class
Consuming the Builder
Understanding the Impact of the Pattern
Variations on the Builder Pattern
Understanding the Pitfalls of the Builder Pattern
Examples of the Builder Pattern in Cocoa
Applying the Pattern to the SportsStore Application
Preparing the Example Application
Defining the Builder Class
Using the Builder Class
Summary

Part III: The Structural Patterns

Chapter 12: The Adapter Pattern
Preparing the Example Project
Creating the Data Sources
Defining the Application
Understanding the Problem That the Pattern Solves
Understanding the Adapter Pattern
Implementing the Adapter Pattern
Variations on the Adapter Pattern
Defining an Adapter as a Wrapper Class
Creating a Two-Way Adapter
Understanding the Pitfalls of the Adapter Pattern
Examples of the Adapter Pattern in Cocoa
Applying the Pattern to the SportsStore Application
Preparing the Example Application
Defining the Adapter Class
Using the Adapted Functionality
Summary

Chapter 13: The Bridge Pattern
Preparing the Example Project
Understanding the Problem That the Pattern Solves
Understanding the Bridge Pattern
Implementing the Bridge Pattern
Dealing with the Messages
Dealing with the Channels
Creating the Bridge
Adding a New Message Type and Channel
Variations on the Bridge Pattern
Collapsing the Bridge
Understanding the Pitfalls of the Bridge Pattern
Examples of the Bridge Pattern in Cocoa
Applying the Pattern to the SportsStore Application
Preparing the Example Application
Understanding the Problem
Defining the Bridge Class
Summary

Chapter 14: The Decorator Pattern
Preparing the Example Project
Understanding the Problem That the Pattern Solves
Understanding the Decorator Pattern
Implementing the Decorator Pattern
Variations on the Decorator Pattern
Creating Decorators with New Functionality
Creating Consolidated Decorators
Understanding the Pitfalls of the Decorator Pattern
The Side-Effect Pitfall
Examples of the Decorator Pattern in Cocoa
Applying the Pattern to the SportsStore Application
Preparing the Example Application
Creating the Decorators
Applying the Decorators
Summary

Chapter 15: The Composite Pattern
Preparing the Example Project
Understanding the Problem That the Pattern Solves
Understanding the Composite Pattern
Implementing the Composite Pattern
Applying the Pattern
Understanding the Pitfalls of the Composite Pattern
Examples of the Composite Pattern in Cocoa
Applying the Pattern to the SportsStore Application
Preparing the Example Application
Defining the Composite Class
Applying the Pattern
Summary

Chapter 16: The Façade Pattern
Preparing the Example Project
Understanding the Problem That the Pattern Solves
Understanding the Façade Pattern
Implementing the Façade Pattern
Applying the Façade
Variations on the Façade Pattern
Understanding the Pitfalls of the Façade Pattern
Examples of the Façade Pattern in Cocoa
Applying the Pattern to the SportsStore Application
Preparing the Example Application
Creating the Façade Class
Applying the Façade Class
Summary

Chapter 17: The Flyweight Pattern
Preparing the Example Project
Understanding the Problems That the Pattern Solves
Understanding the Flyweight Pattern
Implementing the Flyweight Pattern
Creating the Flyweight Protocol
Creating the Flyweight Implementation Class
Adding Concurrency Protections
Creating the Flyweight Factory Class
Applying the Flyweight
Variations on the Flyweight Pattern
Understanding the Pitfalls of the Flyweight Pattern
Understanding the Extrinsic Duplication Pitfall
Understanding the Mutable Extrinsic Data Pitfall
Understanding the Concurrent Access Pitfall
Understanding the Over-optimization Pitfall
Understanding the Misapplication Pitfall
Examples of the Flyweight Pattern in Cocoa
Applying the Pattern to the SportsStore Application
Preparing the Example Application
Creating the Flyweight Protocol and Implementation Class
Creating the Flyweight Factory
Applying the Flyweight
Summary

Chapter 18: The Proxy Pattern
Preparing the Example Project
Understanding the Problems That the Pattern Solves
Understanding the Remote Object Problem
Understanding the Expensive Operation Problem
Understanding the Restricted Access Problem
Understanding the Proxy Pattern
Solving the Remote Object Problem
Solving the Expensive Operation Problem
Solving the Restricted Access Problem
Implementing the Proxy Pattern
Implementing the Remote Object Proxy
Implementing the Expensive Operation Proxy
Implementing the Access Restriction Proxy
Variations on the Proxy Pattern
Implementing a Reference Counting Proxy
Understanding the Pitfalls of the Proxy Pattern
Examples of the Proxy Pattern in Cocoa
Applying the Pattern to the SportsStore Application
Preparing the Example Application
Defining the Protocol, Factory Method, and Proxy Class
Updating the Product Data Store
Sending Stock Level Updates
Summary

Part IV: The Behavioral Patterns

Chapter 19: The Chain of Responsibility Pattern
Preparing the Example Project
Understanding the Problem That the Pattern Solves
Understanding the Chain of Responsibility Pattern
Implementing the Chain of Responsibility Pattern
Creating and Providing the Chain of Responsibility
Applying the Chain of Responsibility Pattern
Variations on the Chain of Responsibility Pattern
Applying the Factory Method Pattern
Indicating Whether Responsibility Was Taken for the Request
Notifying All Links in the Chain
Understanding the Pitfalls of the Pattern
Examples of the Pattern in Cocoa
Applying the Pattern to the SportsStore Application
Preparing the Example Application
Defining the Chain and its Links
Summary

Chapter 20: The Command Pattern
Preparing the Example Project
Understanding the Problem That the Pattern Solves
Understanding the Command Pattern
Implementing the Command Pattern
Defining the Command Protocol
Defining the Command Implementation Class
Applying the Command Pattern
Applying Concurrent Protections
Using the Undo Feature
Variations on the Command Pattern
Creating Composite Commands
Using Commands as Macros
Using Closures as Commands
Understanding the Pitfalls of the Command Pattern
Examples of the Command Pattern in Cocoa
Applying the Pattern to the SportsStore Application
Preparing the Example Application
Implementing the Undo Feature
Summary

Chapter 21: The Mediator Pattern
Preparing the Example Project
Understanding the Problem That the Pattern Solves
Understanding the Mediator Pattern
Implementing the Mediator Pattern
Defining the Meditator Class
Conforming to the Peer Protocol
Implementing Concurrency Protections
Variations on the Mediator Pattern
Putting More Logic Into the Mediator
Generalizing the Mediator-Peer Relationship
Understanding the Pitfalls of the Mediator Pattern
The Single Protocol Pitfall
Examples of the Mediator Pattern in Cocoa
Applying the Pattern to the SportsStore Application
Summary

Chapter 22: The Observer Pattern
Preparing the Example Project
Understanding the Problem That the Pattern Solves
Understanding the Observer Pattern
Implementing the Observer Pattern
Creating the Base Subject Class
Conforming to the Subject Protocol
Conforming to the Observer Protocol
Consuming the Pattern
Variations on the Observer Pattern
Generalizing Notifications
Using Weak References
Dealing with Short-Lived Subjects
Understanding the Pitfalls of the Observer Pattern
Examples of the Observer Pattern in Cocoa
User Interface Events
Observing Property Changes
Applying the Pattern to the SportsStore Application
Preparing the Example Application
Applying the Pattern
Summary

Chapter 23: The Memento Pattern
Preparing the Example Project
Understanding the Problem That the Pattern Solves
Understanding the Memento Pattern
Implementing the Memento Pattern
Implementing the Memento Class
Using the Memento
Variations on the Memento Pattern
Understanding the Pitfalls of the Memento Pattern
Examples of the Memento Pattern in Cocoa
Applying the Pattern to the SportsStore Application
Preparing the Example Application
Implementing the Pattern
Summary

Chapter 24: The Strategy Pattern
Preparing the Example Project
Understanding the Problem That the Pattern Solves
Understanding the Strategy Pattern
Implementing the Strategy Pattern
Defining the Strategies and the Context Class
Consuming the Pattern
Variations on the Strategy Pattern
Understanding the Pitfalls of the Strategy Pattern
Examples of the Strategy Pattern in Cocoa
Cocoa Protocol-Based Strategies
Cocoa Selector-Based Strategies
Applying the Pattern to the SportsStore Application
Summary

Chapter 25: The Visitor Pattern
Preparing the Example Project
Understanding the Problem That the Pattern Solves
Understanding the Visitor Pattern
Implementing the Visitor Pattern
Conforming to the Shape Protocol
Creating the Visitors
Applying the Visitors
Variations on the Visitor Pattern
Understanding the Pitfalls of the Visitor Pattern
Examples of the Visitor Pattern in Cocoa
Applying the Pattern to the SportsStore Application
Summary

Chapter 26: The Template Method Pattern
Preparing the Example Project
Understanding the Problem That the Pattern Solves
Understanding the Template Method Pattern
Implementing the Template Method Pattern
Variations on the Template Method Pattern
Understanding the Pitfalls of the Pattern
Examples of the Template Method Pattern in Cocoa
Applying the Pattern to the SportsStore Application
Summary

Part V: The MVC Pattern

Chapter 27: The Model/View/Controller Pattern
Preparing the Example Project
Understanding the Problem That the Pattern Solves
Understanding the MVC Pattern
Understanding the MVC Application Sections
Implementing the MVC Pattern
Defining the Common Code
Defining the Framework
Creating the Model
Defining the View
Defining the Controller
Completing the Framework
Running the Application
Extending the Application
Variations on the MVC Pattern
Understanding the Pitfalls of the MVC Pattern
Examples of the MVC Pattern in Cocoa
Summary

Index
