### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Pyramids at Giza

## Step 1
The Architect is trying to design a building that will stand the test of time. Think how to create pyramids. There are 3 levels: 5 blocks on the bottom, 3 blocks in the middle, and 1 block on top.

#### ~ tutorialhint 
Think about how the Agent needs to move to place the right number of blocks for each level of the pyramid. At the start, give your Agent ten `Smooth Sandstone` using ``||agent.agent set block or item||``. Then use the ``||agent.agent move||`` block to move your agent forward and for each step use ``||agent.agent place||`` to place a block in the direction you want the block placed.

```ghost
    agent.setItem(SMOOTH_SANDSTONE, 64, 0)
    agent.move(FORWARD, 0)
    agent.place(FORWARD)
    agent.turn(LEFT_TURN)
    for (let index = 0; index < 4; index++) {
    	
    }
```
```template
agent.setItem(SMOOTH_SANDSTONE, 64, 0)
```
```package
```
