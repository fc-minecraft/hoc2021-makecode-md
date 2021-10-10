### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# First Computer Scientist

## Step 1
The computer scientist has created punch cards that contain the instructions for the first computer. But, someone has filled in the holes. Code your AGENT to DESTORY the BROWN BLOCKS to make the cards work.

#### ~ tutorialhint 
Use ``||agent.agent move||`` and ``||agent.agent turn||`` to move your AGENT to each BROWN BLOCK. Then use ``||agent.agent destroy||`` to remove the BROWN BLOCK. Repeat this until all the BROWN BLOCKS are destroyed.

```ghost
    agent.move(FORWARD, 0)
    agent.destroy(FORWARD)
    agent.turn(RIGHT_TURN)
    for (let index = 0; index < 4; index++) {
    	
    }
```
```template
\\
```
```package
```
