up:: [[traversal/multi-hierarchy/b]]

There is a trail of `dir:up`  from `a` -> `b` -> `c`.
However, the hierarchies of the two links are different (`a` -up-> `b`, but `b` -parent-> `c`).
Therefore, the upwards traversal shouldn't consider them as being on the "same" path

Passes if this note only shows a path up to `b`, and `b` only shows a path up to `c`

