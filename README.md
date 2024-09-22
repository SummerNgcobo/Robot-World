# Robot-World

This is a Java-based server-client application for a robot world simulation. The server manages a world with obstacles and robots, and clients can connect to the server to launch and control their own robots.


Features:

Server that manages a world with obstacles and robots
Clients can connect to the server to launch and control their own robots
Robots can move around the world, shoot, and interact with other robots and obstacles
The server keeps track of all robots and their statuses, and can broadcast messages to all clients
The world can be displayed in a GUI, and the server can send updates to the GUI to show the current state of the world
For every robot that joins the server, information about previously-launched robots is sent to the client and is visible
The server can send updates to the client's GUI to show the current state of all robots



System Requirements:

A linux operating system
Java 11 or higher
Maven (for dependency management)
Access to a terminal that supports ANSI colors and Unicode characters
Internet access



Getting Started:
To get started with the Robot Worlds application, follow these steps:

Clone the repository to your local machine
Open the project in your favorite Java IDE (e.g. IntelliJ, Eclipse)
Build and run the Server class to start the server
Build and run the Client class to start a client and connect to the server
Follow the prompts in the client to launch and control your robot


