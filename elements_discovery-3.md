### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Elements of Discovery (Solution)

## Step 1
The below code is the correct solution to the activity. Run the code by pressing the green play button to see it in action.

#### ~ tutorialhint 
Use ``||agent.agent move||`` and ``||agent.agent turn||`` to move your Agent to the green glowing bookcases. Use ``||agent.agent destroy||`` in the direction you want to destroy the green glowing bookcases block. Repeat this until the 3 bookcase blocks are destroyed.

```ghost
    agent.move(FORWARD, 0)
    agent.destroy(FORWARD)
    agent.turn(RIGHT_TURN)
    for (let index = 0; index < 4; index++) {
    	
    }
```
```template
agent.move(UP, 2)
agent.move(FORWARD, 2)
agent.destroy(LEFT)
agent.move(FORWARD, 5)
agent.turn(RIGHT_TURN)
agent.move(FORWARD, 8)
agent.destroy(LEFT)
agent.turn(RIGHT_TURN)
agent.move(FORWARD, 9)
agent.destroy(FORWARD)
```
```package
```
