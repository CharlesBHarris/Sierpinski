# Sierpinski
The javascript file implements a simple algorithm to generate a Sierpinski triangle. Open 
the html file in your browser and the triangle should be displayed. The algorithm relies
upon the fact that the triangle produced is the attractor set of a family of 3 contraction
mappings (Lipschitz constant 0.5) centered at the vertices of the triangle. A random point 
is chosen to start and then each new point is generated by randomly selecting a vertex and
calculating the location of the midpoint of the segment from the vertex to the old point.
The midpoint then becomes the new point and the algorithm iterates 10,000 times, generating
an approximation of the triangle. The Sierpinski triangle is a fractal object having
Hausdorff dimension log(3)/log(2), or approximately 1.58496.