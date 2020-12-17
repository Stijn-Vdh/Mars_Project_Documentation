![logo](img/MTTS.png)

# Martian Travel Tube System

## What are we ?

### Project Concept:

We provide a fast, safe, reliable, fun and fully automatic travel system for dome inhabitants and companies. 
By offering the fastest way of transportation, it grants people less travel time, which translates to more sleep, freetime and worry free lives. 
For companies we offer a separate tubular network with larger pods to guarantee fast deliveries on large shipments. 

### Mission:
Our goal is to realise the fastest lead times possible:

By lead time we are referring to the speed at which goods can be delivered to their destination after placing an order. 
The speed at which a good is ordered and the delivery of it is, through our innovative system, unprecedented.

We are also referring to the efficiency of transporting humans to their desired / required location. 
Decreasing travel time enriches human lives. Response time to emergency situations is drastically lowered. 
This allows our own emergency task force to respond quickly to infrastructural emergencies. 
All other emergency services also benefit from this, increasing safety by a large margin.

### Vision:
Through an easily accessible network of travel tubes we want to 
allow goods and people to travel more efficiently than ever.


## How do we do it ?

By creating a user-friendly mobile focused **client** application that communicates through a REST API and sockets with
our Java **server**. 

MTTS Client main screen             |  MTSS Client quick access
:-------------------------:|:-------------------------:|
![](img/mtts%20main%20screen.jpg)  |  ![](img/mtts%20quick%20access.jpg)

![diagram](https://svgshare.com/i/S00.svg)

The client allows users to easily order pods for personal or package transportation. 

### POC features:

* Order pods for Martian transport
* Order pods for package transport
* Visually display pod route
* A fully animated UI
* An interactive map with all available endpoints
* Notifications
* Location sharing to friends
* Friend list
* Estimated time (travel time, arrival time, …)
* Keep user, trip and financial data in DB
* Add trips to favorites / keep travel history


## Server

### Minimum requirements:

* #### Java version 11 or higher
* #### Gradle

IntelliJ has gradle integration. 

 
### Quick setup:
* [Go to our server repository](https://git.ti.howest.be/TI/2020-2021/s3/project-ii/projects/groep-15/server)
* Clone the repository
* Run the server

Clone the repo through Gitlab: 

![link](img/clone%20repo.png)

Or clone the repo using the commandline:
```shell
git clone https://git.ti.howest.be/TI/2020-2021/s3/project-ii/projects/groep-15/server.git
```
* Run the server through the GUI:

![link](img/run%20server.png)

Or use the terminal:

Navigate to the root of the project and execute

Windows: 
```shell
gradlew.bat run
```
Linux:
```shell
gradlew run
```

The server automatically creates the H2 Database, so no further configuration is needed.
The server should now be running and available for the client.

### Please refer to the server [readme](https://git.ti.howest.be/TI/2020-2021/s3/project-ii/projects/groep-15/server) file for more information. 

## Client

### [link to documentation](https://git.ti.howest.be/TI/2020-2021/s3/project-ii/projects/groep-15/client)

Written by Daniel Vlaeminck and Maarten Vercruysse