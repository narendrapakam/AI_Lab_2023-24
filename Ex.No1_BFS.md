Ex.No: 1 Implementation of Breadth First Search
DATE: 25-02-2025
REGISTER NUMBER : 212222060171
AIM:
To write a python program to implement Breadth first Search.

Algorithm:
Start the program
Create the graph by using adjacency list representation
Define a function bfs and take the set “visited” is empty and “queue” is empty
Search start with initial node and add the node to visited and queue.
For each neighbor node, check node is not in visited then add node to visited and queue list.
Creating loop to print the visited node.
Call the bfs function by passing arguments visited, graph and starting node.
Stop the program.
Program:
graph = {
 '5' : ['3','7'],
 '3' : ['2', '4'],
 '7' : ['8'],
 '2' : [],
 '4' : ['8'],
 '8' : []
}
visited = [] # List for visited nodes.
queue = [] #Initialize a queue
def bfs(visited, graph, node): #function for BFS
 visited.append(node)
 queue.append(node)
 while queue: 
     m = queue.pop(0)
     print (m, end = " ")
     for neighbour in graph[m]:
         if neighbour not in visited:
             visited.append(neighbour)
             queue.append(neighbour)
# Driver Code
print("Following is the Breadth-First Search")
bfs(visited, graph, '5') # function calling 
Output:
Screenshot 2025-03-11 143343

Result:
Thus the breadth first search order was found sucessfully.
