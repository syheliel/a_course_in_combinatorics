- [x] Problem 1F
- [x] Problem 1G
- [x] Problem 1I
- [x] Problem 1J

# Problem 1F
Let fix a vertex v of G. Since each vertex of G has degree ≥ d, there are at least d vertices $v_1,v_2,\dots,v_d$ with  1 hop from v. 
Since the girth of G is 5, not 3. So we know that $v_1,v_2,\dots,v_d$ can't be connected, or a triangle will be created.
Also， girth not equal to 4, so we know that $v_i,v_j(i \not = j)$can't be connected to a same node. Assume that $v_i,v_j$ are connect to x, then the path $v,v_i,x,v_j,v$ will be a polygen of length 4.
So $v_1,\dots,v_d$ will create d(d − 1) new vertices(because degree $v_i$ >= d).Thus, $|V_G| ≥ 1 + d + d(d − 1) = d^2 + 1$

# Problem 1G

For a graph G=(V,E), a node has at most |V|-1 degree. Suppose that every node in the graph has different degree, notice that all the possible degree values are $\{0,1,\dots,|V|-1\}$, then we must have a node N with degree 0 and node M with degree $|V|-1$. Then M must connected to every node in G, with conflicts the 0 degree of N.

# Problem 1I

Intuition:

assume that Q = $\{1,2,3\}$, n=2，then Hamiltonian path for graph is:

11 -> 12 -> 13 -> 23 -> 22 ->  21 -> 31 -> 32 -> 33

# Problem 1J

see [hw6a.dvi (cmu.edu)](https://www.math.cmu.edu/~af1p/Teaching/Combinatorics/F06/hw6a.pdf)