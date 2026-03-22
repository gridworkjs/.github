# gridwork

Composable spatial data structures for JavaScript.

Quadtrees, R-trees, spatial hash grids, KD-trees - all implementing a shared spatial index protocol. Learn one API, pick the data structure that fits your problem. Swap implementations without rewriting your code.

## Packages

| Package | Version | Description |
|---------|---------|-------------|
| [`@gridworkjs/core`](https://github.com/gridworkjs/core) | [![npm](https://img.shields.io/npm/v/@gridworkjs/core)](https://www.npmjs.com/package/@gridworkjs/core) | Geometry primitives (point, rect, circle) and spatial index protocol |
| [`@gridworkjs/quadtree`](https://github.com/gridworkjs/quadtree) | [![npm](https://img.shields.io/npm/v/@gridworkjs/quadtree)](https://www.npmjs.com/package/@gridworkjs/quadtree) | Quadtree spatial index for sparse, uneven point and region data |
| [`@gridworkjs/rtree`](https://github.com/gridworkjs/rtree) | [![npm](https://img.shields.io/npm/v/@gridworkjs/rtree)](https://www.npmjs.com/package/@gridworkjs/rtree) | R-tree spatial index with bulk loading for rectangles and polygons |
| [`@gridworkjs/hashgrid`](https://github.com/gridworkjs/hashgrid) | [![npm](https://img.shields.io/npm/v/@gridworkjs/hashgrid)](https://www.npmjs.com/package/@gridworkjs/hashgrid) | Spatial hash grid for uniform distributions and fast neighbor lookups |
| [`@gridworkjs/kd`](https://github.com/gridworkjs/kd) | [![npm](https://img.shields.io/npm/v/@gridworkjs/kd)](https://www.npmjs.com/package/@gridworkjs/kd) | KD-tree for static point sets and nearest-neighbor queries |
| [`@gridworkjs/query`](https://github.com/gridworkjs/query) | [![npm](https://img.shields.io/npm/v/@gridworkjs/query)](https://www.npmjs.com/package/@gridworkjs/query) | Higher-level queries (radius, KNN, ray, within) against any index |

---

This ecosystem is an experiment in AI-maintained open source. All packages are autonomously built, tested, and refined by AI with human oversight. Regular audits, thorough test coverage, continuous refinement - the emphasis is on high quality, rigorously tested, production-grade code.
