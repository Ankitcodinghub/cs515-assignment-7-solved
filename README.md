# cs515-assignment-7-solved
**TO GET THIS SOLUTION VISIT:** [CS515 Assignment 7 Solved](https://www.ankitcodinghub.com/product/cs515-assignment-7-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;100703&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS515 Assignment 7 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
1 Overview

Let G = (V, E) be an undirected graph. Some vertices of G are red, and the others are blue. Let VR denote the set of red vertices of G, and VB the set of blue vertices of G. The vertex set V of G is the union of the two disjoint sets VR and VB. Likewise, the edge set E of G is the union of three mutually disjoint subsets: the set ERR of edges with both endpoints red, the set EBB of edges with both endpoints blue, and the set ERB of edges with endpoints of two different colors. We have the two induced subgraphs: the red subgraph GR = (VR,ERR), and the blue subgraph GB = (VB,EBB).

A cycle in the red subgraph GR is called a red cycle. Likewise, a cycle in the blue subgraph GB is called a blue cycle. A red or a blue cycle is called monochromatic, since such a cycle consists of vertices of the same color. On the other hand, a cycle in G with vertices of both the colors is called nonmonochromatic. In this assignment, you need to write a program to identify the existence of monochromatic and nonmonochromatic cycles, and print some of them.

In the following figure, a graph is shown. A red cycle in the graph is (0,2,3,0). A blue cycle in the graph is (1,4,8,7,1). These cycles are monochromatic. Two nonmonochromatic cycles in the graph are (0,1,7,6,3,0) and (5,6,7,8,9,5). We assume that a cycle does not contain repeated vertices (except the first and the last ones).

2 Task to be carried out

Perform the following tasks.

2.1 Storing the Graph

You need to store the following information about an undirected graph.

<ul>
<li>The number of vertices in the graph (an integer)</li>
<li>The colors of the vertices (an array of characters r and b)</li>
<li>The vertex numbers (an array of integers): Let G has n vertices. These vertices are naturally numbered as 0, 1, 2, 3, …, n − 1. The red subgraph in the above example has the vertex set 0,2,3,5,6 and blue subgraph has vertex set 1,4,7,8,9.</li>
<li>The edges of the graph: Use the adjacency-list (not matrix) representation to store the edges. Since we are dealing with undirected graphs, for every undirected edge (u,v), v must appear in the adjacency list of u, and u in the adjacency list of v. .</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
2.2 Read and Print a Graph

Write a function readgraph to return a graph G constructed from user inputs. The user first enters the number n of vertices of G, followed by the colors of the vertices, and finally by the list of edges. Each edge is specified by a pair (u, v). It is the responsibility of the user to avoid entering the same edge multiple times. When the user is done with entering the edges, −1 is entered as u in order to indicate the end of the input session.

2.3 Get the Red and Blue Subgraph

Write a function getcolgraph(G, color) that, given the graph G and a color (r or b), generates GR or GB as color suggests, and returns this subgraph.

2.4 DFS traversal in a graph, and detection of cycles

Write a recursive DFS function, and a multi-DFS function for an input graph. During the traversal, look for a back edge and if a back edge is detected, then the cycle causing this back edge is printed along with the colors of the vertices on the cycle. All cycles in a graph are not required to print by the multi-DFS traversal. It suffices to print atmost two cycles corresponding to the back edges.

3 Sample Input Output

<pre>10 //no of vertices
r b r r b r r b b b //color code of the vertices
//edge list terminated by -1
0 1, 0 2, 0 3, 1 3, 1 4, 1 7, 2 3, 2 5, 3 6, 4 7, 4 8, 5 6, 5 9, 6 7, 7 8, 8 9, -1
</pre>
<pre>Original Graph
0-&gt; 1, 2, 3
1-&gt; 0, 3, 4, 7
2-&gt; 0, 3, 5
3-&gt; 0, 1, 2, 6
4-&gt; 1, 7, 8
5-&gt; 2, 6, 9
6-&gt; 3, 5, 7
7-&gt; 1, 4, 6, 8
8-&gt; 4, 7, 9
9-&gt; 5, 8
</pre>
<pre>Red SubGraph
0-&gt; 2, 3
2-&gt; 0, 3, 5
3-&gt; 0, 2, 6
5-&gt; 2, 6
</pre>
6-&gt; 5

<pre>Blue SubGraph
1-&gt; 4, 7
4-&gt; 1, 7, 8
7-&gt; 1, 4, 8
8-&gt; 4, 7, 9
9-&gt; 8
</pre>
<pre>Red Cycles
0-2-3-0 color (r-r-r-r)
0-2-5-6-3-0 color (r-r-r-r-r-r)
</pre>
<pre>Blue Cycles
1-4-8-7-1 color (b-b-b-b-b)
4-7-8 color (r-r-r)
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
<pre>Multi Color Cycles
0-1-7-6-3-0 color (r-b-b-r-r-r)
5-6-7-8-9-5 color (r-r-b-b-b-r)
</pre>
4 Submission

You need to implement the program either using c or c++. You need to include the followings in your submission file-

<ul>
<li>Your C or C++ code</li>
<li>A README file (assign7README.txt) comprising all the necessary documentation is also required. You must also provide option for the input filename and output filename.</li>
<li>Copying programs from others or from other sources and allowing others to copy your program will be equally penalized.</li>
</ul>
</div>
</div>
</div>
