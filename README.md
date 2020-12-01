Client-server network storage (without using Java EE) - Netty implementation.

Basic functionalities:
- File transfer (including directories) by byte protocol: sending files to the server,
downloading files, viewing files on the server for each user, deleting files locally/on the server.
- Files are stored on the server in directories with user's names.
- Authentication. A database is used for storing users.
- The client has a simple graphical interface in JavaFX.
- Tree structure inside user's directory on the server.
- Logging is performed in the AuthHandler class.

For tests: 
  login - l1
  password - p1
