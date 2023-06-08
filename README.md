# Bridging Nodes
Pseudocode for bridging complex state machines.

## Vortex Structure
For states in Vortex:
Even number states connect to even number states in other Vortex state machines.<br />
Odd number states connect to other number states in other vortex state machines.<br />
Compatible states in each vortex must be structured in a way it doesn't matter what state you arrive in.

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
