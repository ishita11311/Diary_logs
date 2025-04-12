# Diary_logs
Here’s a concise, * This repository contains a **Digital Diary App** built with **SQLite** for managing daily journal entries. It utilizes **ACID-compliant transactions** for data integrity and implements core **CRUD operations**. The app is designed for local storage and offers a lightweight, efficient solution for personal journaling.



### **Project Overview**

This repository hosts the source code for a **Digital Diary Application**, leveraging **SQLite** as an embedded database to facilitate the secure, efficient, and organized management of daily journal entries. The application supports fundamental **CRUD** (Create, Read, Update, Delete) operations and ensures data integrity through the use of **ACID-compliant transactions**.

### **Key Features**
- **Relational Data Modeling**: The diary entries are structured in a normalized relational format, ensuring scalability and data integrity. The `diary_logs` table is used to persist daily reflections, including the date and content of each entry.
- **Transactional Integrity**: All database operations are executed within **transactions** to guarantee that updates to the diary entries remain atomic, consistent, isolated, and durable, preventing partial or corrupt data states.
- **SQL Query Proficiency**: Demonstrates advanced SQL skills, such as **SELECT**, **INSERT**, **UPDATE**, and **DELETE** queries, as well as the implementation of **JOIN** operations and custom filtering.

### **Technologies Used**
- **SQLite**: An embedded relational database that provides the flexibility of an SQL database with minimal overhead, ideal for local-first applications.
- **SQL**: The primary language for querying and managing data, which facilitates robust operations on the diary logs.
- **Markdown**: Used for documentation within this repository, including providing a comprehensive overview of the project's functionality and purpose.

### **Objective**
This application aims to provide users with a streamlined, reliable method for recording and tracking personal reflections on a daily basis. It employs SQLite as the backend, making it suitable for lightweight, local storage solutions. The app's modular design allows for easy expansion, including additional features such as user authentication, mood tracking, and tagging.

### **Related Projects**
For a more immersive, interactive experience, explore my **Khan Academy project** that complements this application: [Khan Academy Diary Project](https://www.khanacademy.org/computer-programming/daily-journal-app/6542821177802752).

