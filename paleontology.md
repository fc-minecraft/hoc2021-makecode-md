### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Paleontology Puzzle

## Step 1
Someone has removed bones from the dinosaur skeleton and replaced them with sand. Code your agent to replace the SAND blocks with BONE blocks.

#### ~ tutorialhint 
Use ``||agent.agent set block or item||`` to `Bone Block`. Use ``||agent.agent move||`` to move your agent in front of the SAND block. Use ``||agent.agent destroy||`` to destroy the SAND block and ``||agent.agent place||`` to place a `Bone Block` instead. Repeat this until all the SAND blocks are replaced.


```ghost
    agent.setItem(BONE_BLOCK, 64, 1)
    agent.move(FORWARD, 0)
    agent.destroy(FORWARD)
    agent.place(FORWARD)
    for (let index = 0; index < 4; index++) {
    	
    }
```
```template
\\
```
```package
```
