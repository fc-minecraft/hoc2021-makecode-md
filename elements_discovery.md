### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Elements of Discovery

## Step 1
When the Chemist left the room, someone hid her research inside the bookcases. Code your AGENT to break the green glowing bookcases, so that the research does not remain hidden.

#### ~ tutorialhint 
Use ``||agent.agent move||`` and ``||agent.agent turn||`` to move your AGENT to the green glowing bookcases. Use ``||agent.agent destroy||`` to destroy the green glowing bookcase blocks. Repeat this until all the green glowing bookcase blocks are destroyed.

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
