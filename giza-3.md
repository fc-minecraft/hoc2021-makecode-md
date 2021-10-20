### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Great Pyramid at Giza (Solution)

## Step 1
The below code is the correct solution to the activity. Run the code by pressing the green play button to see it in action.

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
for (let index=0); index < 5; index++){
agent.move(FORWARD, 1)
agent.place(BACK)
}
agent.move(UP, 1)
agent.turn(LEFT_TURN)
agent.turn(LEFT_TURN)
agent.move(FORWARD, 1)
agent.move(FORWARD, 1)
for (let index=0); index < 3; index++){
agent.move(FORWARD, 1)
agent.place(BACK)
}
agent.move(UP, 1)
agent.turn(LEFT_TURN)
agent.turn(LEFT_TURN)
agent.move(FORWARD, 1)
agent.move(FORWARD, 1)
agent.move(FORWARD, 1)
agent.place(BACK)
```
```package
```
