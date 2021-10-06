### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# The Great Wall of China

## Step 1
The Mona Lisa's famous smile is now a frown. Someone has trampled her garden. Use the Agent to place White Glazed Terracotta in a 6x6x6x6 square to begin construction of a beautiful new fountain.


#### ~ tutorialhint 
Give the Agent `White Glazed Terracotta` by using ``||agent.setItem||``, then use the ``||agent.move||`` to move the Agent into position and ``||agent.place||`` to place the `White Glazed Terracotta`.

```ghost
    agent.setItem(WHITE_GLAZED_TERRACOTTA, 64, 1)
    agent.move(FORWARD, 1)
    agent.place(DOWN)
    agent.move(FORWARD, 1)
    agent.place(DOWN)
    agent.move(FORWARD, 1)
    agent.place(DOWN)
    agent.move(FORWARD, 1)
    agent.place(DOWN)
    agent.move(FORWARD, 1)
    agent.place(DOWN)
    agent.turn(RIGHT_TURN)
    agent.move(FORWARD, 1)
    agent.place(DOWN)
    agent.move(FORWARD, 1)
    agent.place(DOWN)
    agent.move(FORWARD, 1)
    agent.place(DOWN)
    agent.move(FORWARD, 1)
    agent.place(DOWN)
    agent.move(FORWARD, 1)
    agent.place(DOWN)
    agent.turn(RIGHT_TURN)
    agent.move(FORWARD, 1)
    agent.place(DOWN)
    agent.move(FORWARD, 1)
    agent.place(DOWN)
    agent.move(FORWARD, 1)
    agent.place(DOWN)
    agent.move(FORWARD, 1)
    agent.place(DOWN)
    agent.move(FORWARD, 1)
    agent.turn(RIGHT_TURN)
    agent.place(DOWN)
    agent.move(FORWARD, 1)
    agent.place(DOWN)
    agent.move(FORWARD, 1)
    agent.place(DOWN)
    agent.move(FORWARD, 1)
    agent.place(DOWN)
    agent.move(FORWARD, 1)
    agent.place(DOWN)
    agent.move(FORWARD, 1)
    agent.place(DOWN)
    for (let index = 0; index < 4; index++) {
    	
    }
```
```template
\\
```
```package
```
