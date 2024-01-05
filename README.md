Sure, here's a template for your README file:

```markdown
# Binary Trees Project

This repository contains solutions to various binary tree-related tasks implemented in C. The tasks cover fundamental operations such as creating nodes, inserting nodes, traversing the tree, and performing various measurements on the tree structure.

## Table of Contents

- [Requirements](#requirements)
- [Tasks](#tasks)
  - [0. New Node](#0-new-node)
  - [1. Insert Left](#1-insert-left)
  - [2. Insert Right](#2-insert-right)
  - [3. Delete](#3-delete)
  - [4. Is Leaf](#4-is-leaf)
  - [5. Is Root](#5-is-root)
  - [6. Pre-order Traversal](#6-pre-order-traversal)
  - [7. In-order Traversal](#7-in-order-traversal)
  - [8. Post-order Traversal](#8-post-order-traversal)
  - [9. Height](#9-height)
  - [10. Depth](#10-depth)
  - [11. Size](#11-size)
  - [12. Leaves](#12-leaves)
  - [13. Nodes](#13-nodes)
  - [14. Balance Factor](#14-balance-factor)
  - [15. Is Full](#15-is-full)
- [How to Use](#how-to-use)
- [License](#license)

## Requirements

- GCC (GNU Compiler Collection)

## Tasks

### 0. New Node

Write a function that creates a binary tree node.

```c
binary_tree_t *binary_tree_node(binary_tree_t *parent, int value);
```

### 1. Insert Left

Write a function that inserts a node as the left-child of another node.

```c
binary_tree_t *binary_tree_insert_left(binary_tree_t *parent, int value);
```

### 2. Insert Right

Write a function that inserts a node as the right-child of another node.

```c
binary_tree_t *binary_tree_insert_right(binary_tree_t *parent, int value);
```

### 3. Delete

Write a function that deletes an entire binary tree.

```c
void binary_tree_delete(binary_tree_t *tree);
```

### 4. Is Leaf

Write a function that checks if a node is a leaf.

```c
int binary_tree_is_leaf(const binary_tree_t *node);
```

### 5. Is Root

Write a function that checks if a given node is a root.

```c
int binary_tree_is_root(const binary_tree_t *node);
```

### 6. Pre-order Traversal

Write a function that goes through a binary tree using pre-order traversal.

```c
void binary_tree_preorder(const binary_tree_t *tree, void (*func)(int));
```

### 7. In-order Traversal

Write a function that goes through a binary tree using in-order traversal.

```c
void binary_tree_inorder(const binary_tree_t *tree, void (*func)(int));
```

### 8. Post-order Traversal

Write a function that goes through a binary tree using post-order traversal.

```c
void binary_tree_postorder(const binary_tree_t *tree, void (*func)(int));
```

### 9. Height

Write a function that measures the height of a binary tree.

```c
size_t binary_tree_height(const binary_tree_t *tree);
```

### 10. Depth

Write a function that measures the depth of a node in a binary tree.

```c
size_t binary_tree_depth(const binary_tree_t *tree);
```

### 11. Size

Write a function that measures the size of a binary tree.

```c
size_t binary_tree_size(const binary_tree_t *tree);
```

### 12. Leaves

Write a function that counts the leaves in a binary tree.

```c
size_t binary_tree_leaves(const binary_tree_t *tree);
```

### 13. Nodes

Write a function that counts the nodes with at least 1 child in a binary tree.

```c
size_t binary_tree_nodes(const binary_tree_t *tree);
```

### 14. Balance Factor

Write a function that measures the balance factor of a binary tree.

```c
int binary_tree_balance(const binary_tree_t *tree);
```

### 15. Is Full

Write a function that checks if a binary tree is full.

```c
int binary_tree_is_full(const binary_tree_t *tree);
```

## How to Use

1. Clone the repository:

```bash
git clone https://github.com/your-username/binary_trees.git
```

2. Compile the source files using GCC:

```bash
gcc -Wall -Wextra -Werror -pedantic binary_tree_print.c main.c task_files.c -o binary_trees
```

3. Run the executable:

```bash
./binary_trees
```
