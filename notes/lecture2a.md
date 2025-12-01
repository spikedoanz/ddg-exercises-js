# what is a "mesh"?

- a __mesh__ could be a simplicial complex, which itself is a graph + oriented faces
  - example data structre: halfedge, 
- __abstract simplicial complexes__ are the discrete version of topological spaces
- a __convex set__ is one in which all points on all lines made between any two
points in the set is strictly in the set
  ? why is it a straight line?
- a __convex hull__ is the smallest convex set which contains all of some set of points
- __affine dependence__ is the extension of linear dependence to points: all
vectors connecting those points have to be linearly independent.
- a __k-simplex__ is the convex hull of k+1 affinely independent points. the points
are then called __vertices__
- __degenerate__ in math usually points a special case where the object loses some properties
  - ex: a degenerate triangle is three points on a line
  - ex: a single point is a 0-simplex
- __barycentric coodinates__ are coordinates in terms of other points (that sum to one)
  - non negative implies inside the shape
  - negative implies outside
  - note: having to sum to one is a result of the requirement for the sum to be affine.
  this is so that it is invariant under translation.

* insight: linear combinations are invariant under linear transforms, and
affine combinations are invariant under affine transforms

* insight: euclidean geometry is special because it has metric tensor = matmul identity
  - collolary: no curvature
  - collolary: parallel transport is path independent (just addition)
  - it apparently also "has the largest possible isometry group", though i don't know
  what this statement means yet
