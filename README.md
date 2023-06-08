# Bridging Nodes
Pseudocode for bridging complex state machines.

## Vortex Structure
~~~
      8               1
      +               +    
     / \             / \   
    /   \           /   \   
   /     \         /     \
7 +       \       /       + 2     8                 1
   \       \     /       /        +                 +
    \       \   /       /        / \               / \
     \       \ /       /        /   \             /   \
      \       X       /        /     \           /     \
       \     / \     /      7 +       \         /       + 2
        \   /   \   /          \       \       /       /
         \ /     \ /            \       \     /       /
          +       +              \       \   /       /
          5       4               \       \ /       /
                                   \       X       /
                                    \     / \     /
                                     \   /   \   /
                                      \ /     \ /
                                       +       +
                                       5       4
~~~
