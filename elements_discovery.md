### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Elements of Discovery

## Step 1
When the scientist left the room, someone hid some of her research inside the bookcases. Use the Agent to break the bookcases that are hiding the missing research.


#### ~ tutorialhint 
Use ``||agent.move||`` to move the Agent towards the bookcases with the green glow and then use ``||agent.destroy||`` to break them.

```ghost
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
    for (let index = 0; index < 4; index++) {
    	
    }
```
```template
\\
```
```package
```
