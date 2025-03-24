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


