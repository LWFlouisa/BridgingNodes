# Bridging Nodes
Pseudocode for bridging complex state machines.

## Vortex Structure

### Basic Rule Structure
For states in Vortex:
Even number states connect to even number states in other Vortex state machines.<br />
Odd number states connect to other number states in other vortex state machines.<br />
Compatible states in each vortex must be structured in a way it doesn't matter what state you arrive in.<br />
The only odd state that shouldn't be shared is the fifth: expiration. It may lead to a dominoe effect.

### Sketch Of Rules In Action
~~~
      8               1               1               8
      +               +               +               +       
     / \             / \             / \             / \      
    /   \           /   \           /   \           /   \     
   /     \         /     \         /     \         /     \    
7 +       \       /       + 2...2 +       \       /       + 7 
   \       \     /       /         \       \     /       /    
    \       \   /       /           \       \   /       /     
     \       \ /       /             \       \ /       /      
      \       X       /               \       X       /       
       \     / \     /                 \     / \     /        
        \   /   \   /                   \   /   \   /         
         \ /     \ /                     \ /     \ /          
          +       +                       +       +
          5       4                       4       8
                  Git Clone       Git Clone


Integer = Functions In Vortex
\ or /  = State Machines
  +     = Function Initialization
...     = Sharepoint / Knowledge Share

( 1 Dormant State
( 2 Sprouting State
( 4 Growing State
( 8 Reproductive State
( 7 Retirement State
( 5 Expiration State
~~~
