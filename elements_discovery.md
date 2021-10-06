### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Elements of Discovery

## Step 1
When the scientist left the room, someone hid some of her research inside the bookcases. Use the Agent to break the bookcases that are hiding the missing research.


#### ~ tutorialhint 
Use ``||agent.agent move||`` to move the Agent towards the bookcases with the green glow and then use ``||agent.agent destroy||`` to break them.

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
