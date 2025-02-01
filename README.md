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
- ## **History and Evolution of C#:**
     Visit: (https://en.wikipedia.org/wiki/C_Sharp_(programming_language))
- ## **Installing .NET SDK & Setting Up Development Environment**
    To start programming in C#, install the .NET SDK:
    - **Installing .NET SDK**
      - Download the .NET SDK from (https://dotnet.microsoft.com/en-us/download)
      - Install it by following the setup instructions.
      - Verify Installation: ```dotnet --version```

    - **Setting Up Visual Studio Code for C#**
        - Install Visual Studio Code from code.visualstudio.com.
        - Install the C# Extension from the Extensions Marketplace.
        - Open VS Code and create a new .cs file.

    - **Setting Up Visual Studio for C#**
        - Install Visual Studio Community Edition.
        - Select “.NET Desktop Development” during installation.
        - Create a new C# Console Application.
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
- ## **Variables and Data Types**
    **C# Data Types:**
      C# provides various data types that can be categorized into **Value Types** and **Reference Types**.
   ## 1. **Value Types:**
     Value types hold the actual data. When a value type is assigned to another variable, a copy of the data is created.
      ### **Numeric Types**

  | **Type**    | **Description**                                                   | **Range**                                                    | **Example**                                                      |
  |-------------|-------------------------------------------------------------------|--------------------------------------------------------------|-----------------------------------------------------------------|
  | `byte`      | 8-bit unsigned integer                                            | 0 to 255                                                     | `byte b = 255;`                                                 |
  | `sbyte`     | 8-bit signed integer                                              | -128 to 127                                                   | `sbyte sb = -100;`                                               |
  | `short`     | 16-bit signed integer                                             | -32,768 to 32,767                                             | `short s = 32767;`                                               |
  | `ushort`    | 16-bit unsigned integer                                           | 0 to 65,535                                                   | `ushort us = 50000;`                                             |
  | `int`       | 32-bit signed integer                                             | -2,147,483,648 to 2,147,483,647                               | `int i = 2147483647;`                                            |
  | `uint`      | 32-bit unsigned integer                                           | 0 to 4,294,967,295                                            | `uint ui = 4000000000;`                                          |
  | `long`      | 64-bit signed integer                                             | -9,223,372,036,854,775,808 to 9,223,372,036,854,775,807       | `long l = 9223372036854775807L;`                                 |
  | `ulong`     | 64-bit unsigned integer                                           | 0 to 18,446,744,073,709,551,615                              | `ulong ul = 18446744073709551615UL;`                             |
   | `float`     | 32-bit single-precision floating-point number                     | ±1.5 × 10^−45 to ±3.4 × 10^38 (7 digits of precision)        | `float f = 3.14f;`                                               |
   | `double`    | 64-bit double-precision floating-point number                     | ±5.0 × 10^−324 to ±1.7 × 10^308 (15–16 digits of precision)  | `double d = 3.14159265358979;`                                    |
   | `decimal`   | 128-bit precise decimal value for financial calculations          | ±1.0 × 10^−28 to ±7.9 × 10^28 (28-29 digits of precision)    | `decimal dec = 19.99m;`                                           |

    ### Boolean Type

    | **Type**    | **Description**                                                   | **Range**                                                    | **Example**                                                      |
    |-------------|-------------------------------------------------------------------|--------------------------------------------------------------|------------------------------------------------------------------|
    | `bool`      | Represents `true` or `false`                                      | `true`, `false`                                              | `bool isActive = true;`                                           |

    ### Character Type

    | **Type**    | **Description**                                                   | **Range**                                                    | **Example**                                                      |
    |-------------|-------------------------------------------------------------------|--------------------------------------------------------------|------------------------------------------------------------------|
    | `char`      | Represents a single 16-bit Unicode character                      | 0 to 65,535                                                   | `char letter = 'A';`                                             |

    ### Struct Types
    Structs are user-defined value types that can contain data and methods. Example: `DateTime`, `Guid`

    | **Type**    | **Description**                                                   | **Example**                                                      |
    |-------------|-------------------------------------------------------------------|------------------------------------------------------------------|
    | `struct`    | User-defined value type that can hold data and methods.           | `struct Point { public int X; public int Y; }`                  |

    ### Enumeration Types
    Enums are used to define a set of named integral constants.

    | **Type**    | **Description**                                                   | **Example**                                                      |
    |-------------|-------------------------------------------------------------------|------------------------------------------------------------------|
    | `enum`      | A set of named integral constants. Example:                       | ```csharp                                                      |
    |             |                                                                   | enum Day { Sunday, Monday, Tuesday, Wednesday, Thursday, Friday, Saturday }; |
    |             |                                                                   | ```                                                             |

  ## 2. Reference Types
    Reference types store references to the data, and the data itself is stored in a different memory location. When a reference type is assigned to another,         they both point to the same object.

  ### String

  | **Type**    | **Description**                                                   | **Example**                                                      |
  |-------------|-------------------------------------------------------------------|------------------------------------------------------------------|
  | `string`    | Represents a sequence of Unicode characters (immutable).         | `string name = "John Doe";`                                      |

  ### Object

  | **Type**    | **Description**                                                   | **Example**                                                      |
  |-------------|-------------------------------------------------------------------|------------------------------------------------------------------|
  | `object`    | The base type of all data types in C#. It can hold any data type. | `object obj = 42;`                                              |

    ### Arrays

  | **Type**    | **Description**                                                   | **Example**                                                      |
  |-------------|-------------------------------------------------------------------|------------------------------------------------------------------|
  | `array`     | A collection of elements of the same type.                        | `int[] numbers = {1, 2, 3, 4};`                                  |

  ### Class

  | **Type**    | **Description**                                                   | **Example**                                                      |
  |-------------|-------------------------------------------------------------------|------------------------------------------------------------------|
  | `class`     | A user-defined reference type. Example:                           | ```csharp                                                        |
  |              |                                                                   |   class Person {                                                 |   
  |             |                                                                    |      public string Name { get; set; }                            |    
  |             |                                                                    |    public int Age { get; set; }                                  |   
                                                                                      |   }```                                                            |     
                                                                                                                                                  

    ### Delegate

    | **Type**    | **Description**                                                   | **Example**                                                      |
    |-------------|-------------------------------------------------------------------|------------------------------------------------------------------|
    | `delegate`  | Represents references to methods with a specific parameter list and return type. | `delegate void MyDelegate(string message);`                     |

    ### Interface

    | **Type**    | **Description**                                                   | **Example**                                                      |
    |-------------|-------------------------------------------------------------------|------------------------------------------------------------------|
    | `interface` | A contract that defines methods, properties, events, or indexers, but does not provide implementation. | `interface IAnimal { void Speak(); }`                           |

    ## 3. Nullable Types
    A nullable type can represent all the values of its underlying type plus `null`.

    | **Type**          | **Description**                              | **Example**                                                     |
    |-------------------|----------------------------------------------|---------------------------------------------------------------|
    | `Nullable<T>` or `T?` | Represents a type that can also hold `null`. | `int? myNullableInt = null;`                                   |

    ## 4. Tuple Types (C# 7.0 and later)
    A tuple is a data structure that allows you to group multiple values of different types together.

    | **Type**          | **Description**                              | **Example**                                                     |
    |-------------------|----------------------------------------------|---------------------------------------------------------------|
    | `Tuple`           | A data structure that stores multiple values. | `var tuple = (1, "Hello", 3.14);`                               |

---

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
