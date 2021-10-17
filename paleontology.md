### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Paleontology Puzzle

## Step 1
Someone has removed bones from the dinosaur skeleton and replaced them with sand. Code your Agent to DESTROY the SAND BLOCKS and PLACE BONE blocks.
#### ~ tutorialhint 
Use ``||agent.agent set block or item||`` to give your Agent a `Bone Block`. Use the ``||agent.agent move||`` to move your Agent and then ``||agent.agent destroy||`` in the direction you want the block SAND blocks destroyed and ``||agent.agent place||`` to place a `Bone Block` in the direction you want the block placed. Repeat this until the right number of blocks are placed.

```ghost
    agent.setItem(BONE_BLOCK, 64, 1)
    agent.move(FORWARD, 0)
    agent.destroy(FORWARD)
    agent.place(FORWARD)
    for (let index = 0; index < 4; index++) {
    	
    }
```
```template
agent.setItem(BONE_BLOCK, 64, 1)
```
```package
```
