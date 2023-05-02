Download Link: https://assignmentchef.com/product/solved-cosc310-assignment-9-graphs
<br>
The objectives of this assignment are to:

<ul>

 <li>Gain further experience with using interfaces.</li>

 <li>Gain experience with implementation of a Graph.</li>

 <li>Gain experience using Sets.</li>

 <li>Gain further experience with recursions.</li>

 <li>Gain experience with using graphs to solve problems.</li>

 <li>Continue to practice good programming techniques.</li>

</ul>

<h3>Task:</h3>

<strong>Step 1:</strong>

Add to ALGraph.java an implementation of depthFirstSearch and bestSearch.  Use the Dijkstra algorithm as the implementation for bestSearch.

<strong>Step 2: </strong>

Add to the graph in TestGraph an edge from Detroit to Pittsburgh with a distance of 400.

Modify the TestGraph to print the path results from breadthFirstSearch, depthFirstSearch, and bestSearch for paths from Philadelphia to Detroit and Fort Wayne to Toledo.

<strong>Step 3: </strong>

Create a new test program, TestGraph2, using the same graph of step 3, only use a Road object for edges.  The Road object must have a distance and a speed limit attributes.  Use the same distances, only use 80 as the speed on the path from Pittsburgh, Cleveland, Columbus, Indianapolis, Fort Wayne, to Chicago, and 25 for all other edges.  Then find and print the breadthFirstSearch, depthFirstSearch, bestSearch using distance, and bestSearch using time for the path from Philadelphia to Chicago.

<strong>Step 4: </strong>

Create a new test program, TestGraph3 for the <strong>directed</strong> graph in Figure 10.26 (shown below). Then find and print the breadthFirstSearch, depthFirstSearch, bestSearch for paths from 0 to 4 and from 1 to 0.

<h3>Bonus 10 points</h3>




Provide an aStarSearch method.  This method has the same arguments as the bestSearch except uses the A Star algorithm to determine the best path.  For this problem a City class must be defined.  A city will hold the city name along with coordinates.  Use the straight line distance between two cities (based on the city coordinates – that is the square root of the sum of square of delta x and square of delta y) as the heuristic guiding the A Star algorithm.  Use the coordinates on the following graph:

Run the aStarSearch for “Toledo” to “Fort Wayne”.

<h3>Deliverables:</h3>

<ul>

 <li>zip file containing the sources and class files for ALGraph, Graph, and TestGraph, TestGraph2 and TestGraph3. The .zip file must be named [Your name]Asmt9.zip.</li>

 <li>Files of your captured output from running the test programs.</li>

</ul>