# C4 Architecture model for Scheduling and Time-Tracking Application for Remote Teams

The C4 architecture model is a hierarchical approach to the software architecture visualization that consists of a set of diagrams at different levels of abstraction.

## Level 1: System Context Diagram

![image](/Assignment2/SystemContextDiagram.png)

At level 1, system context diagram shows the boundaries of the system and its interactions with external actors. We have the main external actor, i.e., “User”, who interacts with the Scheduling and Time Tracking Application.

## Level 2: Container Diagram

![image](/Assignment2/Container.png)

At level 2, a container diagram illustrates the high-level components and their interactions within the system. We have three main components:

1. User Interface (Web App): It represents the web application layer responsible for presenting the user interface using HTML,CSS and JavaScript.
2. Application Sever: It represents the server-side component that hosts and runs the application. It handles user requests, orchestrates the business logic and communicates with other components.
3. Database: It represents the persistence layer of the application. It stores and retrieves data related to user profiles, schedules, time entries and other relevant information.

## Level 3: Component Diagram

At level 3, the component diagram delves deeper into the internal components within each container. It highlights the key components and their relationships:

1. User Interface (Web App): Represents the web application layer responsible for presenting the user interface using HTML, CSS, and JavaScript.

2. Application Server:
   a. Controller: represents the component responsible for handling user requests, processing input data, and invoking appropriate services.
   b. Service: Represents the business logic layer of the application. It encapsulates the core functionalities, such as scheduling tasks, tracking time, and performing various operations on the data.
   c. Repository: Represents the component responsible for interacting with the database, performing data access, and implementing data persistence.
   d. External API Integration: It handles integration with external systems, such as calendar APIs or time-tracking APIs, for data synchronization and external operations.

3. Database: Represents the database components responsible for storing and managing the application’s data.
