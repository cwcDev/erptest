📝 Jira Ticket
Title: Implement C++ OOP Module with Database Integration and Git Version Control

Type: Task
Priority: Medium
Assignee: [Developer Name]
Sprint: [Sprint Name or Number]
Labels: C++, OOP, SQLite, Git, backend

Description:

Develop a C++ application module that demonstrates core object-oriented programming (OOP) concepts and interacts with a SQLite database. This task includes writing modular, maintainable code that encapsulates user data within a class structure and supports basic persistence via SQLite. Additionally, the entire project should be version-controlled using Git, with a clear commit history and an appropriate .gitignore file.

Acceptance Criteria:

 A User class is implemented using C++ with proper constructors and encapsulated member variables.

 The class includes methods to insert user data into a SQLite database and retrieve all users.

 Database schema is created programmatically if it doesn’t exist.

 Error handling is in place for database operations (insert, query, etc.).

 The project is initialized with Git and includes a .gitignore file that excludes compiled binaries and database files.

 README file is added with instructions to build and run the project.

 Code compiles and runs using g++ or via a provided CMakeLists.txt (if applicable).

 At least two commits are pushed to the Git repository: one for scaffolding, and one for feature completion.

Technical Notes:

Use the sqlite3 library for database interaction.

Keep the implementation in a single file (main.cpp) for simplicity.

Optional: Use CMake for build automation.
