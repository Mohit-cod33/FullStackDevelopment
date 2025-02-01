# **FullStackDevelopment**
This repo contains learning and development of Full Stack journey.
<br>
## **Technologies**
  |S.N|Tech. Name|
  |---|----------|
  |1|C#|
  |2|DotNet Core|
  |3|Entity FrameWork|
  |4|Rest Apis|
  |5|Microservices|
  |6|Java Script|
  |7|Html|
  |8|Css|

# **C#**
  ## **Topics**
## 1. Introduction to C#
- ## **<u>What is C#?</u>**
   <p>
     C# (pronounced "C-Sharp") is a modern, object-oriented programming language developed by Microsoft as part of its .NET initiative. It was first released in        2002 and has since evolved into a versatile and powerful language used for a wide range of applications.
      C# is designed to be simple, modern, and easy to learn, especially for developers familiar with languages like C, C++, or Java. It is a strongly-typed            language, which means that data types are checked at compile time, reducing errors and improving code reliability.

    ### <u>**Key Features of C#**</u>
    - **Object-Oriented:** C# is a fully object-oriented language, allowing developers to create reusable code and build complex applications with ease.
    - **Cross-Platform:** C# can be used to develop applications for Windows, Linux, macOS, and mobile platforms like iOS and Android using frameworks such as           Xamarin and .NET MAUI.
    - **Large Standard Library:** C# has a vast standard library that includes a wide range of pre-built classes and functions, making it easy to perform common          tasks without writing a lot of custom code.
    - **Integration with Microsoft Technologies:** C# integrates well with other Microsoft technologies, such as .NET, Azure, and Visual Studio, providing a             seamless development experience.
    - **Community Support:** C# has a large and active community, which means there are plenty of resources, tools, and libraries available to help developers.
    - **Modern Features:** Supports LINQ, asynchronous programming (async and await), pattern matching, and more.
    - **Exception Handling:** Provides robust error handling with try, catch, finally, and throw statements.
    - **Security:** Strong security features with managed code execution and access control mechanisms.
    - **Rich Standard Library:** Comes with an extensive set of libraries for various functionalities.
    - **Multi-threading and Parallelism:** Supports concurrent execution using Thread, Task, and Parallel programming.
    - **Language Integrated Query (LINQ):** Provides a powerful querying capability for collections, databases, and XML.
    - **Event-Driven Programming:** Supports event handling through delegates and event handlers.
    - **Strongly Typed:** Type safety helps prevent runtime errors by enforcing strict data types.
    -  **Automatic Memory Management:** The built-in garbage collector manages memory automatically.

    ### **Applications of C#**
    C# is used in various domains, including:
    - **Desktop Applications:** C# is widely used for developing desktop applications, especially those targeting Windows platforms.
    - **Web Applications:** C# is a popular choice for building web applications and web services using frameworks like ASP.NET.
    - **Mobile Applications:** C# can be used to develop cross-platform mobile applications using Xamarin and .NET MAUI.
    - **Game Development:** C# is extensively used in game development, particularly with the Unity game engine.
    - **Machine Learning:** C# can be used for developing machine learning applications using frameworks such as ML.NET.
    - **IoT Applications:** C# can be used to develop IoT applications using .NET IoT libraries.
   </p>
- History and Evolution of C#
- Features of C#
- ## **Installing .NET SDK & Setting Up Development Environment**
    To start programming in C#, install the .NET SDK:
    - Installing .NET SDK
      Download the .NET SDK from (https://dotnet.microsoft.com/en-us/download)
      Install it by following the setup instructions.
      Verify Installation: ```dotnet --version```

    - Setting Up Visual Studio Code for C#
        Install Visual Studio Code from code.visualstudio.com.
        Install the C# Extension from the Extensions Marketplace.
        Open VS Code and create a new .cs file.

    - Setting Up Visual Studio for C#
        Install Visual Studio Community Edition.
        Select “.NET Desktop Development” during installation.
        Create a new C# Console Application.
- ## **Writing & Running a Simple C# Program**
       ```csharp
        using System;
        class Program
        {
          static void Main()
          {
            Console.WriteLine("Hello, World!");
          }
        }
      

---

## 2. Basics of C#
- Syntax and Structure
- Variables and Data Types
- Constants and Readonly
- Type Casting
- Operators (Arithmetic, Logical, Bitwise, etc.)
- Comments in C#

---

## 3. Control Flow Statements
- Conditional Statements (if, else, switch)
- Looping Statements (for, while, do-while, foreach)
- Jump Statements (break, continue, return, goto)

---

## 4. Methods & Functions
- Defining Methods
- Method Parameters (in, out, ref, params)
- Method Overloading
- Recursion

---

## 5. Object-Oriented Programming (OOP) in C#
- Classes and Objects
- Constructors & Destructors
- Encapsulation & Access Modifiers
- Properties & Indexers
- Inheritance (Single, Multilevel, Multiple via Interfaces)
- Polymorphism (Method Overriding, Method Overloading)
- Abstract Classes & Interfaces
- Sealed Classes & Methods
- Partial Classes & Methods
- Static Classes and Members

---

## 6. Exception Handling
- try, catch, finally, throw
- Custom Exceptions
- Best Practices in Exception Handling

---

## 7. Collections & Generics
- Arrays
- Lists (List<T>, ArrayList)
- Dictionaries (Dictionary<TKey, TValue>, Hashtable)
- Stacks (Stack<T>) & Queues (Queue<T>)
- Sets (HashSet<T>, SortedSet<T>)
- Generics (Generic Classes, Methods, Constraints)

---

## 8. Delegates & Events
- What are Delegates?
- Single & Multicast Delegates
- Anonymous Methods & Lambda Expressions
- Events in C# (event keyword, Event Handlers)
- Func, Action, and Predicate Delegates

---

## 9. LINQ (Language Integrated Query)
- Introduction to LINQ
- LINQ Query Syntax vs. Method Syntax
- Filtering, Sorting, and Grouping Data
- Aggregation Functions (Sum, Max, Min, Average, Count)
- Joining Tables (Join, GroupJoin)

---

## 10. File Handling & Streams
- Reading & Writing Files (File, FileStream, StreamReader, StreamWriter)
- Working with Directories (Directory, DirectoryInfo)
- Serialization & Deserialization (Binary, XML, JSON)

---

## 11. Multithreading & Parallel Programming
- Introduction to Threads (Thread, ThreadPool)
- Synchronization (lock, Monitor, Mutex, Semaphore)
- Asynchronous Programming (async, await, Task, Task<T>)
- Parallel Programming (Parallel.For, Parallel.Invoke)

---

## 12. Memory Management & Performance Optimization
- Garbage Collection
- IDisposable & using Statement
- Value Types vs. Reference Types
- Boxing & Unboxing
- Best Practices for Performance Optimization

---

## 13. Reflection & Dynamic Programming
- Reflection API (Assembly, Type, MethodInfo, PropertyInfo)
- Creating and Invoking Types Dynamically
- Attributes ([Obsolete], [Serializable], Custom Attributes)

---

## 14. Working with Databases (ADO.NET & Entity Framework)
- Connecting to Databases using ADO.NET
- Executing Queries (SqlCommand, SqlDataReader)
- Using DataTable, DataSet, DataAdapter
- Entity Framework Core (Code First, Database First)
- Performing CRUD Operations with EF Core
- Migrations in EF Core

---

## 15. Web Development with ASP.NET Core
- Introduction to ASP.NET Core
- MVC Architecture (Model, View, Controller)
- Razor Pages
- Dependency Injection in ASP.NET Core
- Working with APIs (RESTful APIs, Swagger, Postman)
- Authentication & Authorization (JWT, OAuth)
- Middleware & Filters

---

## 16. Design Patterns in C#
- Singleton
- Factory
- Builder
- Adapter
- Strategy
- Repository & Unit of Work
- Dependency Injection

---

## 17. Unit Testing & Test-Driven Development (TDD)
- Introduction to Unit Testing
- Writing Tests using xUnit/NUnit
- Mocking Dependencies (Moq)
- Writing Integration Tests

---

## 18. Advanced Topics
- Dependency Injection in Depth
- Microservices Architecture
- Working with gRPC
- SignalR for Real-Time Communication
- Distributed Caching with Redis
- Message Queues (RabbitMQ, Kafka)

  
## **Projects**
  |S.N|Project Name|Discription|
  |---|------------|-----------|
  ||||
  ||||
