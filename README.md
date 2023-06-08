# Bridging Nodes
Pseudocode for bridging complex state machines.

## Vortex Structure
For states in Vortex:
Even number states connect to even number states in other Vortex state machines.<br />
Odd number states connect to other number states in other vortex state machines.<br />
Compatible states in each vortex must be structured in a way it doesn't matter what state you arrive in.

~~~
      8               1       |       1               8
      +               +       |       +               +       
     / \             / \      |      / \             / \      
    /   \           /   \     |     /   \           /   \     
   /     \         /     \    |    /     \         /     \    
7 +       \       /       + 2 | 2 +       \       /       + 7 
   \       \     /       /    |    \       \     /       /    
    \       \   /       /     |     \       \   /       /     
     \       \ /       /      |      \       \ /       /      
      \       X       /       |       \       X       /       
       \     / \     /        |        \     / \     /        
        \   /   \   /         |         \   /   \   /         
         \ /     \ /          |          \ /     \ /          
          +       +           |           +       +
          5       4           |           4       8


Integer = Functions In Vortex
\ or /  = State Machines
  +     = Function Initialization
...     = Sharepoint / Knowledge Share

( 1 Dormant State
( 2 Record  Audio
( 4 Convert Audio To Tokens
( 8 Use Tokens As Prolog Fact
( 7 Consult Knowledge Base
( 5 Retrieve Knowledge From Knowledge Base
~~~
