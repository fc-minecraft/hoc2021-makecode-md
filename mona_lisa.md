### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# The Mona Lisa

## Step 1
The Mona Lisa's famous smile is now a frown. Someone has trampled her garden. Use the Agent to place White Glazed Terracotta in a 6x6x6x6 square to begin construction of a beautiful new fountain.


#### ~ tutorialhint 
Give the Agent `White Glazed Terracotta` by using ``||agent.agent set item||``, then use ``||agent.agent move||`` to move the Agent into position and ``||agent.agent place||`` to place the `White Glazed Terracotta`.

```ghost
    agent.setItem(WHITE_GLAZED_TERRACOTTA, 64, 0)
    agent.move(FORWARD, 0)
    agent.place(FORWARD)
    agent.turn(RIGHT_TURN)
    for (let index = 0; index < 4; index++) {
    	
    }
```
```template
\\
```
```package
```
