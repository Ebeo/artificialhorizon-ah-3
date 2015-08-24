This small Java application is an Artificial Horizon and lets you to debug, study, analyze, improve, better tuning or whatever your IMU or kalman application in a visual way.
It could be adapted to display just angle attitude information from your DCM or application.

Since it does use a serial connection I wrote it with a microcontroller in mind, so the application is strongly aimed to get data from your micro and display it.

It has been written in Java to assure max portability and doesn't require any installation.

You can choose between 2 versions. They are almost the same, but the improved one (AH-3+) has a better and smarter markers drawing and gives you the feeling as it moves on a spheric surface.
Anyway, both versions are your disposal in case you feel "sick" of the improved version.

The only steps to perform to run the application is an installation or updating of your JRE (or Java Runtime Environment) up to 1.6.0 (at least) and install the free serial library for java rxtx from this link: www.rxtx.org

In the same site you can find examples and instruction how to install them (basically you need to download and copy 3 files)

You get lots of informations by reading the README file in the tar archive.

NOTE:
This software has been distribuited in a jar archive and developed in java.
In other words doesn't need any installation routine, the program will be compiled and run by your JVM (Java Virtual Machine) by simply clicking or double clicking on the .jar file.