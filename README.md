# Documentation Lab Activity 
This activity aims to demonstrate the power of good code documentation, and
to give you some practice using code that you do not know the implementation
details of. You should complete this assignment using only the Javadoc comments
to know what methods to use and how, and you should not need to look at the
body of these methods at all.

Your assignment is as follows:
- You will implement the method furthestNode in the ProblemSet class.
- This method takes as parameters a String representing the path of a file to be read and a String representing the starting node to find your paths from.
- The file stores an edge list representation of a weighted directed graph that can have negative edge weights but no negative cycles.
- The furthestNode method needs to parse the graph represented in the file and return the node that has the shortest path from the starting node with the greatest distance.

Once you have completed the furthestNode method and confirmed that it works using the given tests,
you should write your own Javadoc comment on that method in the same way that comments are written for
the given methods.

To help you accomplish this, the following have been provided:
- A Utilities class, which has several static methods for file reading and various conversions and calculations you may find useful
- A Graph class, which can be used to construct a Graph object from a given adjacency list and find shortest paths on that graph
- A set of very simple tests that should suffice to tell you if your solution works.

### Hints
If you are having trouble figuring out your solution, you may find the following helpful:
- The process of what furthestNode needs to do can be broken down into the following steps:
    - Parse the given file to make an edge list of the graph
    - Convert that edge list into an adjacency list and use that adjacency list to construct a Graph object
    - Find the shortest path to every node in the graph from the starting node
    - Determine which of the shortest paths has the greatest distance and return the end node of that path
- You will not need to use every one of the provided methods. Read each method's description carefully to determine whether or not you will need to use it.
- Your solution only needs to be a few lines long. If your solution is more than 4-6 lines of code, you are probably manually doing something that the starter code can do for you.

