Requirement:Your implementation here should be fast and non-recursive. The test program will test your implementations of these functions on very large (e.g., 100k node) trees. All your implementations should run in linear time and should be able to label a 100k node tree in a tenth of a second or so.  Your implementation should work even if the tree is extremely unbalanced.

This assignment asks you to use binary tree traversals to make nice(ish) drawings of binary trees. To do this, you will implement some of the functions in the GeometricTree class.

inorderDraw(): this function assigns x coordinates to nodes so that each node gets a distinct x-coordinate, and each node receives an x-coordinate between that of its two children 


leftistDraw(): this function assigns x coordinates to nodes so that each node receives the minimum x-coordinate it can without overlapping nodes on its own level 


balancedDraw(): this function does not preserve the ordering of left and right children. Instead, it computes the sizes of the two subtrees of the root. The smaller of the two is drawn directly below the root. The larger of the two is drawn directly to the right of the root, but far enough away that it doesn't intersect the drawing at the root. 

