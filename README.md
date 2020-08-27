# 3D Vertex Model

![author](https://img.shields.io/badge/Author-Ali%20Hashmi-blue)

![version](https://img.shields.io/badge/Mathematica%20version-12.1%2B-green)
![Dependency](https://img.shields.io/badge/dependencies-IGraphM-red) 

`under active development`


The project contains an implementation of a vertex model to simulate biological tissues in 3D. The repository currently houses the Mathematica [notebook](https://github.com/alihashmiii/3DVertexModel/blob/master/vertex%20model%20sim/vertex%20model%203D.nb) ([PDF](https://github.com/alihashmiii/3DVertexModel/blob/master/vertex%20model%20sim/vertex%20model%203D.pdf)) for simulating an infinite sheet of cells in a monolayer. However, this code can be easily modified to simulate cells in 3D agglomerates/aggregates - which are essentially easier to simulate than an infinite sheet. In this implementation the cells can exchange neighbours (T1 transitions).

`vertex model sim - contains the code for modeling infinite sheet of cells`

`vertex model aggregate - will contain code for modeling an agglomerate of cells`


### To-Do List:
- cell division event to create a new polyhedron
- cell death to remove a polyhedron from the mesh


## Notes

- **If you use or modify the code to disseminate the results in a publication, you would need to cite the author's repository and explicitly ask for permission. Ofcourse I will not decline any request** 

- The code is based on and is a modification of *Okuda et al 2012, "Reversible network reconnection model for simulating large deformation in dynamic tissue morphogenesis"*

- install [IGraphM](https://github.com/szhorvat/IGraphM) 
to use the `SubIsomorphicQ` function
