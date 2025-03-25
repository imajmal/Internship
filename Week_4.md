# Week_4
## Functions

- Functions in programming are essential building blocks that allow developers to structure code in a modular and reusable way. A function is a block of code designed to perform a specific task. Functions execute only when explicitly called by the user, ensuring that unnecessary computations do not occur. This approach enhances the efficiency of a program and makes debugging easier.

- A return-type function provides a value of a specific datatype after execution. In Java, functions must specify the datatype keyword when defining them, ensuring type safety. However, JavaScript does not require explicit type declarations, offering greater flexibility but requiring careful handling to avoid unintended errors. Functions play a crucial role in organizing large programs by breaking them down into smaller, manageable components.

## Class and Object

- A class serves as a blueprint for creating objects, defining the attributes and behaviors of a specific entity in a program. It allows programmers to structure their code effectively by grouping related functionalities within a single unit. Initially, class fields do not contain data, but they can be accessed and assigned values using objects.

- An object is an instance of a class that provides access to the class's properties and methods. Objects allow for the manipulation and retrieval of data stored within a class. Multiple instances of a class can be created, each storing different values while maintaining the structure defined by the class. This enables object-oriented programming (OOP) principles such as encapsulation, inheritance, and polymorphism.A constructor is a special function within a class that initializes objects upon creation. It has the same name as the class and ensures that necessary fields are set up as soon as an object is instantiated. A parameterized constructor enables the passing of external data to initialize fields dynamically, making objects more versatile and reducing redundant code.

## Backend Server

- I developed a backend server using JavaScript with the Express.js framework to manage employee attendance. The server plays a crucial role in storing and retrieving employee-related data, including personal details such as name, age, ID, and attendance records. Additionally, it tracks leave records, specifying reasons for absences.
To manage data efficiently, I utilized an array to store employee information. Functions within the backend process and update this data dynamically whenever required. By implementing server-side logic, I ensured that employee records are maintained securely and can be retrieved as needed.

The server supports two primary HTTP methods:

- POST: This method is responsible for storing values in an array or a database. Using the Bruno API tester, data can be submitted through localhost and securely stored.

- GET: This method allows for the retrieval of requested data from the server. Upon receiving a request, the server fetches the corresponding response from the database and delivers it to the client.

To optimize request handling, separate routes are defined for different API endpoints. This modular approach ensures maintainability and scalability, allowing the server to accommodate additional functionalities in the future.

## PostgreSQL Database

-To enhance data storage capabilities, I integrated PostgreSQL as the backend database for my Express.js server. PostgreSQL is an open-source object-relational database management system (ORDBMS) known for its reliability and performance. It provides robust support for handling structured data and complex queries.

- To establish a connection between PostgreSQL and the backend server, I utilized the pg package. This package enables seamless interaction between the database and server-side application logic. PostgreSQL supports two primary connection methods:

- Pool Connection: This method is preferred for large-scale environments as it allows multiple connections to be maintained efficiently.

- Client Connection: This method is commonly used in development environments where a single connection suffices for local testing and debugging.

- Database setup involves creating a dedicated database with a unique username and password for access control. Additionally, schemas and tables are designed to store structured employee data, ensuring efficient data management Within the PostgreSQL database, structured tables and columns are defined to store various employee records. SQL queries are used to perform essential data operations such as inserting, updating, deleting, and altering records. These queries enable seamless data manipulation while ensuring integrity and consistency across all records.

## Server Functionalities

- The backend server is designed to streamline employee attendance tracking by storing relevant information and monitoring leave records. It ensures accurate record-keeping and enhances operational efficiency through well-defined API functionalities.

- Several API methods have been implemented to facilitate seamless database interactions:

- POST: This method allows new employee records to be inserted into the database. It plays a critical role in capturing and storing user-provided data.

- GET: This method enables the retrieval of employee information. When a client requests specific data, the server processes the request and returns the corresponding records.

- PATCH: This method facilitates modifications to existing records using SQL queries. It is particularly useful when updating employee details or modifying attendance records.

- DELETE: This method enables the removal of records when necessary. It ensures that outdated or irrelevant data does not clutter the database.


## ORM Object Relational Model

- TypeORM is a popular ORM for TypeScript and JavaScript applications, particularly in Node.js environments. It provides a way to interact with databases using an intuitive, object-oriented approach. With TypeORM, developers can define entities (database tables) as TypeScript classes, making it easier to manage relationships, queries, and migrations efficiently.

- Among the various ORM libraries available, TypeORM is one of the most popular choices for JavaScript and TypeScript applications, especially in the Node.js ecosystem. It is designed to work seamlessly with TypeScript, allowing developers to define their database structure using classes and decorators,TypeORM supports various relational databases, including MySQL, PostgreSQL, SQLite, MariaDB, and SQL Server, making it a flexible choice for different projects. It provides a powerful set of features such as automatic migrations, relationship management, and query building, which simplify database handling.

- In TypeORM, database tables are represented as entities (TypeScript classes). Each entity corresponds to a table in the database, and each property in the class represents a column in that table. This allows developers to define and interact with their database schema using an object-oriented approach.

- TypeORM makes working with databases in Node.js applications much simpler and more efficient. It eliminates the complexity of raw SQL queries and brings the power of object-oriented programming to database management. 



## Loops
- We do not use loop in any part of our program because of its repitative nature if we did not gave the end point to it it will lead in to the cluster of the program and make us lose more storage in the cloud and make losses in both time and resource.Improper use of loops without defining an endpoint can lead to infinite iterations, consuming excessive memory and processing power. This can result in performance issues, increased resource usage, and unnecessary storage costs, making it crucial to manage loops effectively to optimize both time and computational resources.
## For loop
-  A for loop is one of the most commonly used loops in programming, especially when the number of iterations is known beforehand. It consists of three main components: initialization, condition, and increment or decrement. The initialization step sets up a control variable, the condition determines how long the loop will continue executing, and the increment or decrement step updates the control variable after each iteration. This loop is ideal for iterating through arrays, performing calculations, or executing a block of code a specific number of times. Since the loop control variable is explicitly defined, it ensures a predictable and structured execution, making it a preferred choice for scenarios where iteration limits are clear.
## while loop
-  while loop is used when the number of iterations is not predetermined, executing continuously as long as a specified condition remains true. Unlike a for loop, a while loop does not require an explicit initialization or update step; it only relies on the condition. This makes while loops useful for cases where iterations depend on user input, sensor data, or real-time system conditions. However, while loops must be carefully managed to prevent infinite execution, as failing to update the condition properly can cause the loop to run indefinitely, leading to performance degradation and system crashes. To avoid such issues, developers should ensure that conditions are updated within the loop and that there is a clear exit strategy.

# Responsibility

- In my internship, I know that learning and improving is completely up to me. Since I want to become a developer, I have to put in the effort to understand new things and practice regularly. My main task is coding in JavaScript, but I’m still figuring things out. Every day, I come across things I don’t fully understand . I search online, go through documentation, and experiment with different ways to solve problems. If I still can’t figure it out, then I ask my mentor for help.Having a mentor is great, but I also know that I can’t depend on them for every little thing. If I always ask for help right away, I won’t actually learn how to solve problems on my own. So, I try to be patient and work through things myself first. Sometimes, I feel stuck for a long time, but when I finally get something to work, it feels really satisfying.One thing I’ve realized is that learning to be a developer takes  of practice. It’s not something that happens in a few days or weeks. Some days, I feel like I’m making progress, and other days, I feel completely lost. But I’ve learned that the key is to  and not get discouraged. Even when something seems difficult, I try to break it down into smaller parts and work through it step by step.  

- Time management is another thing I’m trying to improve. It’s easy to get distracted or leave things for later, but I know that if I do that, I’ll just end up with more work stacked. So, I try to plan my tasks and stay focused. It doesn’t always go perfectly, but I’m getting better at managing my time.  

- Apart from my daily tasks, I also try to learn new things on my own. There’s so much to explore in development, and I don’t want to limit myself to just what I’m assigned. If I come across a new concept, I make a note of it and try to research it later. I also practice by working on small exercises and projects because I’ve realized that actually writing code helps me learn faster than just reading about it.Even small bugs take hours to fix,every mistake I make teaches me something new, and over time, I’ll get better at debugging and writing cleaner code.  

- At the end of the day, my progress depends on me. My mentor can guide me, but I have to put in the effort to learn, practice, and improve. I still have a long way to go, but as long as I stay consistent and keep pushing myself, I know I’ll get better.  

