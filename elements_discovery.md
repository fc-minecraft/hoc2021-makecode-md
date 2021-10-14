### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Elements of Discovery

## Step 1
When the chemist left the room, someone hid her research inside the bookcase. Code your Agent to DESTROY the 3 green glowing bookcases, so that she can share her discoveries. 

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
\\
```
```package
```
