### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# First Computer Scientist

## Step 1
Punch cards were one of the first ways people "programmed" computers. The computer scientist designed the first set of punch cards, but before she was able to send them someone filled all the holes in. Use your agent to break the brown blocks to make the cards work again.


#### ~ tutorialhint 
Use ``||agent.move||`` to move the Agent above the brown blocks, and then use ``||agent.destroy||`` to break the block below it.

```ghost
    agent.move(FORWARD, 1)
    agent.destroy(DOWN)
    agent.move(FORWARD, 2)
    agent.destroy(DOWN)
    agent.move(FORWARD, 2)
    agent.destroy(DOWN)
    agent.move(FORWARD, 1)
    agent.turn(RIGHT_TURN)
    agent.move(FORWARD, 2)
    agent.turn(RIGHT_TURN)
    agent.move(FORWARD, 1)
    agent.destroy(DOWN)
    agent.move(FORWARD, 2)
    agent.destroy(DOWN)
    agent.move(FORWARD, 2)
    agent.destroy(DOWN)
    for (let index = 0; index < 4; index++) {
    	
    }
```
```template
\\
```
```package
```
