# Conversion of DIMACS Road Graphs to PACE Tree Decomposition Challenge Format

The [9-th DIMACS challenge](http://www.dis.uniroma1.it/challenge9/download.shtml) focued on shortest path computations. During the challenge several benchmark instances were made available. These are graphs that represent road networks. This repository contains a conversion of these graphs to the [PACE 2016](https://pacechallenge.wordpress.com/track-a-treewidth/) tree decomposition challenge format.

## History of the Data

The USA benchmark instances are based upon a [TIGER data set](http://www2.census.gov/geo/tiger/) released by the [US Census Bureau](http://www.census.gov/). The original road graphs were build by the organizers of the DIMACS challenge and are available at [the contests website](http://www.dis.uniroma1.it/challenge9/download.shtml). Since their appearance the data has been used in numerous publications. I converted the graphs to the PACE 2016 format. In the resulting graph nodes correspond to geographic positions and edges connect two positions between which there is a road. The resulting graphs are guaranteed to has no multi edges, no reflexive loops, and are guarenteed to be connected. The node IDs of the converted graphs are identical to original DIMACS graphs. The edge IDs differ because I sorted them and removed multi-edges. Geographic positions of the nodes are available from the [original contest website](http://www.dis.uniroma1.it/challenge9/download.shtml).

## Publications

Please cite the following book if use the graphs in a publication:

* The Shortest Path Problem: Ninth DIMACS Implementation Challenge.
  Camil Demetrescu and Andrew V. Goldberg and David S. Johnson.
  2009.

