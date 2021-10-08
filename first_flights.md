### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# First Flight

## Step 1
One of the first planes are about to take off at any minute. But, there are holes in the runway! Code your AGENT to fill the holes.

#### ~ tutorialhint 
Give the AGENT a `Dirt` block to start by using ``||agent.agent set block or item||``. Then use ``||agent.agent move||`` to send your AGENT to the hole. Fill each hole using ``||agent.agent place||`` block. Repeat ``||agent.agent move||`` and ``||agent.agent place||`` until all the holes are filled.

```ghost
    agent.setItem(DIRT, 64, 0)
    agent.move(FORWARD, 0)
    agent.place(FORWARD)
    for (let index = 0; index < 4; index++) {
    	
    }
```
```template
\\
```
```package
```
