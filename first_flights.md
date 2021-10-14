### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# First Flight

## Step 1
1One of the first planes is about to take off, but there are holes in the runway! Code your Agent to fill the holes with `Dirt` blocks. 

#### ~ tutorialhint 
Give the Agent a `Dirt` block to start by using ``||agent.agent set block or item||``. Then use ``||agent.agent move||`` to send your Agent to the hole. Fill each hole using ``||agent.agent place||`` block in the direction you want the block placed. Repeat ``||agent.agent move||`` and ``||agent.agent place||`` until all the holes are filled.

```ghost
    agent.setItem(DIRT, 64, 0)
    agent.move(FORWARD, 0)
    agent.place(FORWARD)
    for (let index = 0; index < 4; index++) {
    	
    }
```
```template
blocks.onStart("run", function () {
    agent.setItem(DIRT, 64, 0)
})

```
```package
```
