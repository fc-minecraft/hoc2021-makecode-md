### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Elements of Discovery (Debug)

## Step 1
There's something wrong with the below code. Press the green play button to run it to see what happens, and then debug it to see what's wrong and what changes are needed to make it work.

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
agent.move(UP, 3)
agent.move(FORWARD, 2)
agent.destroy(LEFT)
agent.move(FORWARD, 5)
agent.turn(LEFT_TURN)
agent.move(FORWARD, 8)
agent.destroy(LEFT)
agent.turn(RIGHT_TURN)
agent.move(FORWARD, 8)
agent.destroy(FORWARD)
```
```package
```
