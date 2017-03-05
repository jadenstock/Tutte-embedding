# Tutte-embedding
Tutte's embedding is a simple way of embedding a planar graph into the plane. That is to say, it will take a planar graph and assign coordinates to each vertex so you can print the graph using something like matplotlib.
You can read more about it here: https://en.wikipedia.org/wiki/Tutte_embedding

Here I provide a function to compute Tutte's embedding from a dictionary representation of a graph. I have added a feature that ensures that two nodes don't get mapped to the same location, a problem with the standard Tutte embedding.
