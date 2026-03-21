# gridwork

spatial data structures for javascript.

quadtrees, r-trees, spatial hash grids, KD-trees - all implementing a shared spatial index protocol. learn one API, pick the data structure that fits your problem.

every index supports the same operations: insert, remove, search, nearest. swap implementations without rewriting your code.

## packages

| package | description |
|---------|-------------|
| `@gridworkjs/core` | geometry primitives and spatial index protocol |
| `@gridworkjs/quadtree` | point and region quadtrees |
| `@gridworkjs/rtree` | r-tree with bulk loading |
| `@gridworkjs/hashgrid` | spatial hash grid |
| `@gridworkjs/kd` | KD-tree for static point sets |
| `@gridworkjs/query` | higher-level queries against any index |
