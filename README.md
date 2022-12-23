# Assignment2
Building a server-client Web Application using Dockers
- Server container will create a checksum and text file with random text in it and send both to the client.
- Client container will get the text and checksum, checks the checksum and store the received text file in the volume.

Using Docker compose tool to create a multi-container application.
- Creaitng a containers with docker file.
- creating volumes and mouting it with serverdata or clientdata.
- Creating a user defined network using host driver.
- Mounting the containers to the network.
