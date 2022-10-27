# 0x1D. C - Binary trees
```C```, ```Group project```, ```Algorithm```, ```Data structure```
<br>
<strong>From</strong>:Aug 22, 2022 6:00 AM<br>
<strong>To</strong>: Aug 26, 2022 6:AM

## Basic Binary Tree
```
/**
 * struct binary_tree_s - Binary tree node
 *
 * @n: Integer stored in the node
 * @parent: Pointer to the parent node
 * @left: Pointer to the left child node
 * @right: Pointer to the right child node
 */
struct binary_tree_s
{
    int n;
    struct binary_tree_s *parent;
    struct binary_tree_s *left;
    struct binary_tree_s *right;
};

typedef struct binary_tree_s binary_tree_t;

```
