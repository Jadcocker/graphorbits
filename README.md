# graphorbits
A repository for the orbits of graphs under the action local complementation, complete up to n=9 vertices.

This work refers to the work "title goes here", which is free to acess at https://arxiv.org/abs/XXXX.XXXXX.


## Orbit data:
  
  The files, 'nqubitorbitsCi.csv' contain the data for each of the n vertex orbits generated by local complementation, where isomorphic *are not* considered as equal.

  The files, 'nqubitorbitsLi.csv' contain the data for each of the n vertex orbits generated by local complementation, where isomorphic *are* considered as equal.

  Table headings are: 
  
    i, |LC|, Orbit edgelist, Edgelabels for orbit, graphlist

    i   		 - Entanglement class index, 
    |LC|		 - Number of vertices in the orbit, 
    graphlist	 - List of graphs that are contained in the orbit
	    		   Orbit edgelists are given in terms of the index of the graph given in the graphlist

			   
  An Example: 
    The orbit edgelist (1-1, 1-2, 2-1, 3-1, 3-3, 4-2, 6-5, 7-6) specifies the orbit as a directed graph with two vertices and three directed edges.
	
    The edgelabel object '(2-1, (1, 2, 6, 7))' states that the edge 2-1 of the orbit in its row should be labelled with "(1, 2, 6, 7)". These are the local complementations that take graph 1 of the orbit to graph 2. The edgelists of graphs 1 and 2 are found as the first two entries in graphlist.


  Note:
    Directed edges are given both for 'L' and 'C' orbits. In both 'L' and 'C' orbits all edges are bidirectoinal, but in 'L' orbits the labels of edges going in different directions can be different.

    Hence only labelled L graphs should be displayed as directed graphs.


## Mathematica files:
  
  Mathematica scripts, 'printorbitCi.nb' and 'printorbitLi.nb' generate plots of the same type as found in our manuscript for all of the classees explored.
  
  The assosciated orbit Mathematica data files ('.mx') contain all of the orbits are also supplied, in Mathematica's proprietry data format.



