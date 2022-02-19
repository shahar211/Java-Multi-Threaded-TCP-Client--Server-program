# Java-Multi-Threaded-TCP-Client--Server-program
Java Multi-Threaded TCP Client- Server program With Bellman–Ford algorithm BFS and DFS

In this project I used java to build a Tcp server that can handle multiple clients using threads. each client that connects the server have it's own thread and able to send request to the server without waiting.

the server is capable to prefrom the following tasks: 1.Create a new random Matrix by the number of rows and columns that the clients passes.

2.Create a new random weighed Matrix, the clients passes the number of rows, columns and the max weight the matrix will have.

3.Find how many connected componnets are in the matrix, using DFS to find the connceted componnets, the function runs on the matrix rows and columns and for each new connceted componnet it found it sends the index to new thread to find the fully new connected componnet, then return the client a list containing the connected componnets in the graph.

4.Find the shortest paths from index x to index y, Using BFS to find all the paths from x to y and then finding each one is the shortest, and return to the client a list containing the shortest path.

5.Submarine Game, a submarine definition in the matrix has at leats two 1's in vertical or at leats two 1's horizontal, the minimale distance between two submarine is at least one empty squate., to find the submarine first the fuction finds the connected componnets for each componnete a new thread is beening used to find the height and max area of the submarine to detarmine of it's legal submarine or not. finaly the server sends the client a the numbr of submarines found in the graph.

6.Find the shortest paths on a weighted graph, using BellmanFord algoritham and threads the servers finds the shortes weighted path on the grahp from node x to node y and return the path to the client.

