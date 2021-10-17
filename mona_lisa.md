### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# The Mona Lisa

## Step 1
The Mona Lisa has a frown, not her famous smile. This is because her garden has been destroyed. You will need to PLACE `White Glazed Terracotta` blocks, so that they form a square outline which is 6 blocks in length by 6 blocks in width.

#### ~ tutorialhint 
Use ``||agent.agent set block or item||`` to give your Agent a `White Glazed Terracotta` block. Use the ``||agent.agent move||`` to move your Agent and then ``||agent.agent place||`` to place a block in the direction you want the block placed. Repeat ``||agent.agent move||`` and ``||agent.agent place||`` until the right number of blocks are placed.

```ghost
    agent.setItem(WHITE_GLAZED_TERRACOTTA, 64, 0)
    agent.move(FORWARD, 0)
    agent.place(FORWARD)
    agent.turn(RIGHT_TURN)
    for (let index = 0; index < 4; index++) {
    	
    }
```
```template
agent.setItem(WHITE_GLAZED_TERRACOTTA, 64, 0)
```
```package
```
