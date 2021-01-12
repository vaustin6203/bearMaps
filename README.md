# Bear Maps
A web mapping application simialr to Google Maps. I implemented the back end of the web server, where given a URL, the program generates a map of the region, which
gets displayed in the web browser. There are four parts to this project.
1. Map Rastering: Given coordinates of a rectangular region of the world and the size of the web browser window, provide images of the appropriate resolution that cover that region.
2. Routing: Given a start and destination latitude and longitude, provide street directions between those points.
3. Autocomplete: Given a string, find all locations that match that string.
4. Written Directions: Augments the routing from Part 2 to include written driving directions.
This project uses the MinPQ and K-D Tree data structures created in a previous project and an AI I built using the A* algorithm which can solve arbitrary state space traversal problems.
