# RobotRock - ConUHacks2017

##What it does
Our simple robot runs and stops from user input from a webpage and can capture/save images on click, all without requiring an internet connection.

##How we built it
Button clicks on the locally-hosted webpage trigger writing certain codes to a text file. The Arduino connects to this network and reads the text file, with different motor movements based on the command. The camera is enabled by a smartphone mounted on the robot, which through IP Webcam gets assigned an IP. This IP is then embedded in the webpage so the user can see what the robot is seeing.
Photos can be snapped of the robot's current view as well.
