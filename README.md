# Dijkstra-s-Algorithm-

Dijkstra's algorithm allows us to find the shortest path between any two vertices of a graph. It differs from the minimum spanning tree because the shortest distance between two vertices might not include all the vertices of the graph.

Input/Output of code – 

![image](https://user-images.githubusercontent.com/65345575/180661102-e5686129-ddd8-4dda-ab4a-f0c448026feb.png)

Explanation of working of the code –

![e1](https://user-images.githubusercontent.com/65345575/180661599-75a58a96-3dc6-43d5-8362-278f596f57e4.PNG)

Distance from node 1 to 2: 24

Distance or cost from node 1 to 4: 20

Distance or cost from node 3 to 1: 3

Distance or cost from node 4 to 1: 12


![e2](https://user-images.githubusercontent.com/65345575/180661642-aecb7306-9418-4b5d-8e33-9ccd5fcb6a29.PNG)

Edge relaxation process

Suppose u = 1, v = 2, d(u, v) = 24

d= distance 

d(u) = 0; distance from source to source is 0.

Initial d(v) = inf;

So, if  d(v) > d(u, v) + d(u) : then 

          d(v) = d(u, v) + d(u) 
          
          

example – 

      if d(2) > d(1, 2) + d(1) then
      
            d(2) = d(1, 2) + d(1)  d(2) = 24 + 0 = 24
            
        
Using this relaxation process we find all the shortest distances:

So, our final result will be this 



Shortest distance from node 1 to 1: 0

Shortest distance from node 1 to 2: 24

Shortest distance from node 1 to 3: 3 

Shortest distance  from node 1 to 4: 15


![e3](https://user-images.githubusercontent.com/65345575/180661665-6ea2d056-30b7-475c-899f-25b1c32f99b5.PNG)


