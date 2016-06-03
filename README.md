# Simple-Aesthetic-Graph-Generator-(ML)

My short attempt at making any given graph (with nodes and edges) seem 'visually appealing' in iPython rather than arranging it randomly.

To do this, I modelled the edges as springs (which try to minimize the tension in the spring, i.e. the length of the edge) and make the nodes 'repel' each other (the closer they are, the stronger the repulsion).

Then using the concepts of 'Hill Climbing/Simulated Annealing' which I learning in Aj.Piti's Numerical Method Class, I chose a variation of the 'Spring Embedded Graph' function as my cost function. I tried to minimize the cost iteratively by reducing the 'spring tension' the edge or 'repulsion force' of node chosen at random.

The process I have used should be somewhat similar to some of Wolfram Alpha's or NX Library's Graph Drawing Algorithms. In fact, I used a variation of Wolfram's Spring Embedding equation shown here (http://reference.wolfram.com/language/tutorial/GraphDrawingIntroduction.html#194525651).

All in all, it was fun experimenting with a cool Machine Learning concept I had just learned!
