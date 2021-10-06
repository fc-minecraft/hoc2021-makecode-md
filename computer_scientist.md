### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# First Computer Scientist

## Step 1
This Computer Scientist designed the first set of punch cards, but before she was able to send them someone filled all the holes in. Use your agent to break the brown blocks to make the cards work again.


#### ~ tutorialhint 
Use ``||agent.agent move||`` to move the Agent above the brown blocks, and then use ``||agent.agent destroy||`` to break the block below it.

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
