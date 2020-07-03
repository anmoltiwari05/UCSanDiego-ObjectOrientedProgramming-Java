# UCSanDiego-ObjectOrientedProgramming-Java

For my Peer-graded assignment, I implemented a visualization of Airports and flight routes

![123](https://user-images.githubusercontent.com/49480794/86497193-48acfb80-bd9e-11ea-8232-bff6d83cd2ee.png)

Implementation of this Applet was done on the dataset ("airports.dat") provided. 
Initially, all the airports are visible in the form of black circles on the world map. 
I've added certain functionalities (hovering, mouse clicks) so that the user can interact with the map. 
Moreover, a thorough usage of Processing library was done in order to provide better visualization.

Following are the functionalities that I've implemented:
* Hovering over an airport marker will show the Airport name.
* After clicking on an airport, all the airports WHICH are not in contact with that particular airport will get HIDDEN. Moreover, the routes of that airport will be shown using SimpleLinesMarker.
* Also, clicking on an airport will change the markers color (yellow) and size (twice as before). 

Code for this assignment can he found [here](https://github.com/anmoltiwari05/UCSanDiego-ObjectOrientedProgramming-Java/blob/master/UCSDUnfoldingMaps/src/module6/AirportMap.java)
