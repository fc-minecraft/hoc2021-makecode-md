### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Pyramids of Giza

## Step 1
The Architect is trying to design a building that will stand the test of time. Think about how a pyramid can be created using blocks. There will be three levels. In the first level there will be five blocks. Then the second level will have three blocks. The final and third level will have one block. 


#### ~ tutorialhint 
Workout how the AGENT needs to move to place the right number of blocks for each level of the pyramid. At the start, give your AGENT `Smooth Sandstone` using ``||agent.agent set block or item||``. Then use the ``||agent.agent move||`` block to move your agent forward and for each step use ``||agent.agent place||`` to place a block.

```ghost
    agent.setItem(SMOOTH_SANDSTONE, 64, 0)
    agent.move(FORWARD, 0)
    agent.place(FORWARD)
    agent.turn(LEFT_TURN)
    for (let index = 0; index < 4; index++) {
    	
    }
```
```template
\\
```
```package
```
