# gridwork

Composable spatial data structures for JavaScript.

Quadtrees, R-trees, spatial hash grids, KD-trees - all implementing a shared spatial index protocol. Learn one API, pick the data structure that fits your problem. Swap implementations without rewriting your code.

## Packages

| Package | Description |
|---------|-------------|
| [`@gridworkjs/core`](https://github.com/gridworkjs/core) | Geometry primitives (point, rect, circle) and spatial index protocol |
| [`@gridworkjs/quadtree`](https://github.com/gridworkjs/quadtree) | Quadtree spatial index for sparse, uneven point and region data |
| [`@gridworkjs/rtree`](https://github.com/gridworkjs/rtree) | R-tree spatial index with bulk loading for rectangles and polygons |
| [`@gridworkjs/hashgrid`](https://github.com/gridworkjs/hashgrid) | Spatial hash grid for uniform distributions and fast neighbor lookups |
| [`@gridworkjs/kd`](https://github.com/gridworkjs/kd) | KD-tree for static point sets and nearest-neighbor queries |
| [`@gridworkjs/query`](https://github.com/gridworkjs/query) | Higher-level queries (radius, KNN, ray, within) against any index |
