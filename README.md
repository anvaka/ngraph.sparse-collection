ngraph.sparse-collection
========================

This repository is a subset of the University of Florida [sparse matrix collection](http://aws.amazon.com/datasets/2379).

Each file in this repository has the following format:

``` js
// it can be consumed as common js module:
module.exports = { 
 "recordsPerEdge": 3,
 "links": [...],
 "description": "..."
};
```

`links` is a flat array of all links (edges) in the graph. Each link is represented by two or three numbers: `fromId`, `toId` and optionally associated `data` (when `recordsPerEdge` is 3);

Usage
=====

This example shows how to transform a matrix into a [graph](https://github.com/anvaka/ngraph.graph):

``` js
// This collection is huge. Import concrete graph only
// to reduce amount of browserified package:
var mtxObject = require('ngraph.sparse-collection/HB/plat1919'),
    mtxParser = require('ngraph.serialization/mtx'),
    graph = mtxParser.loadFromObject(mtxObject);
    
// now you can use graph for analysis:
console.log(graph.getLinksCount());
```

How it's done
=============

This collection was generated from public data set of [University of Florida Sparse Matrix Collection](http://aws.amazon.com/datasets/2379). I've mounted image to ec2 host, and then with help of this [100 lines of code](https://github.com/anvaka/sparsematricesconverter) converted small subset of `HB` and `LPnetlib` folders into CommonJS module.

Caveat
------
Conversion itself is done with [mtx parser](https://github.com/anvaka/ngraph.serialization/blob/master/mtx/mtxParser.js). To save space this parser does not save loops (edges which start and end at the same vertex). Please let me know if it's a deal breaker - I'll make sure to fix this.


Citation
--------
* T. A. Davis, The University of Florida Sparse Matrix Collection, ACM Transactions on Mathematical Software (submitted, 2009), also available as a tech report at http://www.cise.ufl.edu/~davis/techreports/matrices.pdf 
* I. S. Duff, R. G. Grimes, and J. G. Lewis, Sparse Matrix Test Problems, ACM Transactions on Mathematical Software, vol. 15, no. 1. pp. 1-14, 1989, http://doi.acm.org/10.1145/62038.62043
