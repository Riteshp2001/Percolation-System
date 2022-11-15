# Percolation-System
This is the visualization tool in java-programming language to estimate the value of the percolation threshold via Monte Carlo simulation. 
All thanks to sir Sedgewick and sir Kevin Wayne for creating this awesome course project on coursera [ALGORITHMS](https://in.coursera.org/learn/algorithms-part1).
Basically it's an extended version of Union-Find algorithm in which we estimate the threshold of system when it percolates (in short when the upper bound interacts with the lower bound of the Matrix )

# Problem Statement

**Write a program to estimate the value of the percolation threshold via Monte Carlo simulation.**

download the algs4.jar file from repo and install it into your desired compiler.
To access a class in algs4.jar, you need an import statement, such as the ones below:

import edu.princeton.cs.algs4.StdRandom.

import edu.princeton.cs.algs4.StdStats.

import edu.princeton.cs.algs4.WeightedQuickUnionUF.

Note that your code must be in the default package; if you use a package statement, the autograder will not be able to assess your work.

**Percolation**. 
Given a composite systems comprised of randomly distributed insulating and metallic materials: what fraction of the materials need to be metallic so that the composite system is an electrical conductor? Given a porous landscape with water on the surface (or oil below), under what conditions will the water be able to drain through to the bottom (or the oil to gush through to the surface)? Scientists have defined an abstract process known as percolation to model such situations.

**The Model.**
We model a percolation system using an n-by-n grid of sites. Each site is either open or blocked. A full site is an open site that can be connected to an open site in the top row via a chain of neighboring (left, right, up, down) open sites. We say the system percolates if there is a full site in the bottom row. In other words, a system percolates if we fill all open sites connected to the top row and that process fills some open site on the bottom row. (For the insulating/metallic materials example, the open sites correspond to metallic materials, so that a system that percolates has a metallic path from top to bottom, with full sites conducting. For the porous substance example, the open sites correspond to empty space through which water might flow, so that a system that percolates lets water fill open sites, flowing from top to bottom.)

-> one of example of how the percolation system visualization looks like if the system percolates is:

[![mutt dark](https://github.com/Riteshp2001/Percolation-System/blob/main/Test_Data/sedgewick60.png)](https://github.com/Riteshp2001/Percolation-System/blob/main/Test_Data/sedgewick60.png)

<iframe
    width="640"
    height="480"
    src="https://youtu.be/GNBNFPVjPA4"
    frameborder="0"
    allow="autoplay; encrypted-media"
    allowfullscreen
>
</iframe>

**Be sure to test out other file data :)**
