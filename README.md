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

Running instructions:

Running the server


Run the server:

 $ mvn exec:java -Dexec.mainClass="robot_worlds_13.server.Server"




The port number and address is visible server side, when you run the Server class



Running the client:


Run the client, without the gui:

 $ mvn exec:java -Dexec.mainClass="robot_worlds_13.client.Client"
     
 or

 $ mvn exec:java -Dexec.mainClass="robot_worlds_13.client.Client" -Dexec.args="ip_address port"

 e.g mvn exec:java -Dexec.mainClass="robot_worlds_13.client.Client" -Dexec.args="20.20.19.0 2201"




Running the client with the gui:

 Use vscode / intelliJ and run the Client.java class




Ensure you are connected to the correct server and port (The port number is visible server side, when you run the Server class)



Run tests:


Run the tests with the following command:

 mvn test






Usage:

Client commands:
Here are some basic commands you can use in the client to control your robot:

forward <steps>: Move the robot forward by the specified number of steps
back <steps>: Move the robot backward by the specified number of steps
left: Turn the robot to the left
right: Turn the robot to the right
look: Show the current state of the world around the robot
state: Show the current state of the robot
fire: Shoot a bullet in the current direction of the robot
repair: Repair the robot's shields
reload: Reload the robot's ammo
off: Quit the client and disconnect from the server



Server commands:
Here are some basic commands you can use to control your server:

robots: lists all robots in server
dump: lists the state of the world
quit: quit the server




Contributing:
We welcome contributions to the Robot Worlds project! To contribute, follow these steps:

Fork the repository
Create a new branch for your feature or bugfix
Make your changes and commit them to your branch
Push your changes to your forked repository
Create a pull request from your forked repository to the original repository



Contributors:

Summer Ngcobo
Sindiswa Zama
Nkosikhona Mlaba
Thobile Mvuni



