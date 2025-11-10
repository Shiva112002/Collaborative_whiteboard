# Collaborative_whiteboard

Collaborative Whiteboard Application in Java using RMI

How to run: BEFORE EXECUTION

Make sure all the files (User.java, UserInterface.java, RegistryService.java, RegistryServiceImpl.java) are in same folder.
Compile the files by executing "javac *.java" in terminal.
Create stubs for Registry service and User files as: "rmic RegistryServiceImpl" and "rmic User" respectively.
FOR REGISTRY SERVICE:

Execute Registry Service program by executing the following command in terminal: "java RegistryServiceImpl ". Replace with the name you want to give to Registry service.

Example: java RegistryServiceImpl Registry

FOR USERS:

Execute User program by executing: "java User ". Replace: with the name you want to give to User. (E.g. Santosh) with hex code for this user's colour. (E.g. #FF0000 for Red) with the host address. (E.g. 192.168.0.8) with the name of Registry.

Example: java User James #FF0000 192.168.0.8 Registry

