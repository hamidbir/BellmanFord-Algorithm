# BellmanFord-Algorithm With Kotlin
----------------------------------
hi dear (BellmanFord Algorithm With Kotlin)
Solves single shortest path problem in which edge weight may be negative but no negative cycle exists.

This algorithm works correctly when some of the edges of the directed graph G may have negative weight. When there are no cycles of negative weight, then we can find out the shortest path between source and destination.

It is slower than Dijkstra's Algorithm but more versatile, as it capable of handling some of the negative weight edges.

![bellman](https://user-images.githubusercontent.com/44016199/59676610-2a994b00-91dd-11e9-9df8-718892e0c3fc.png)

# Applied example
---------------------------------
magine a scenario where you need to get to a baseball game from your house. Along the way, on each road, one of two things can happen. First, sometimes the road you're using is a toll road, and you have to pay a certain amount of money. Second, sometimes someone you know lives on that street (like a family member or a friend). Those people can give you money to help you restock your wallet. You need to get across town, and you want to arrive across town with as much money as possible so you can buy hot dogs. Given that you know which roads are toll roads and which roads have people who can give you money, you can use Bellman-Ford to help plan the optimal route.

Instead of your home, a baseball game, and streets that either take money away from you or give money to you, Bellman-Ford looks at a weighted graph. The graph is a collection of edges that connect different vertices in the graph, just like roads. The edges have a cost to them. Either it is a positive cost (like a toll) or a negative cost (like a friend who will give you money). So, in the above graphic, a red arrow means you have to pay money to use that road, and a green arrow means you get paid money to use that road. In the graph, the source vertex is your home, and the target vertex is the baseball stadium. On your way there, you want to maximize the number and absolute value of the negatively weighted edges you take. Conversely, you want to minimize the number and value of the positively weighted edges you take. Bellman-Ford does just this.

![bell](https://user-images.githubusercontent.com/44016199/59824263-deb5e580-9345-11e9-900a-79da5fb649f3.gif)


