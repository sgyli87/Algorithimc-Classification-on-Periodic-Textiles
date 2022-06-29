# Algorithimc-Classification-on-Periodic-Textiles
[A computational topology project conducted in DSTA group]

Entangled periodic networks are vitally important
and they exist in structures of various subjects
including biomolecules, metal-organic frameworks
(MOFs) and textiles. From a topological point of
view, textile structures may be considered as
embeddings of circles in a thickened torus [1] and
thus can be investigated using the mathematical tools
of knot theory.


Knot theory, as the study of mathematical knots in
topology, has strong dependency upon diagrams
which are difficult to be computed with and much
work has been done on converting diagrams to string
codes. One well known representation is the Gauss
Code of a knot, and it has been recently extended to
the notion of textile code [2].
In order to map out all possible textile structures, an
exhaustive list of all possible textile codes of a given
length is needed, however, the computation time of
this list grows in size of O(n!) under permutations on
labels of crossings. Therefore, it is necessary to first
remove a proportion of the list which contains codes
that are either redundant, or equivalent to codes with
lower complexity in the sense of their textile
representations. Meanwhile, an algorithm has been
implemented to further remove any unrealizable
codes [2].


However, having done all of these, there are still
codes that represent textiles that are the same under
ambient isotopic deformation, or the selection of
‘unit cell’, which simply depends on how to segment
a given textile into periodic unit patterns.
This project starts from this point, an algorithm and
its code implementation in Python are desired to
automate the calculation where a textile code is taken
and the output is Gauss code of its corresponding
kernel [3], and thus to eliminate any duplicates by
examining the Alexander Data [3] from the obtained
Gauss code with the help of existing Python libraries.

An example algorithm designed to convert textile code to Gauss code of the 
kernel and its implementation in Python are presented here by consent from DSTA @ U of Liverpool.

Topological Computational Libaries:
https://www.sagemath.org/
https://snappy.math.uic.edu/

Background Reading Recommended:
http://kurlin.org/projects/periodic-geometry-topology/textile-structures.pdf
