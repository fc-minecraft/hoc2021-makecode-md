### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# First Flight (Debug)

## Step 1
There's something wrong with the below code. Press the green play button to run it to see what happens, and then debug it to see what's wrong and what changes are needed to make it work.

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
agent.setItem(DIRT, 64, 1)
for (let index = 0; index < 3; index++) {
    agent.move(FORWARD, 1)    	
    agent.place(UP)
}
agent.move(FORWARD, 2)  
agent.move(RIGHT, 2)  
for (let index = 0; index < 3; index++) {
    agent.move(FORWARD, 1)    	
    agent.place(UP)    	
}
agent.move(FORWARD, 2)  
agent.move(RIGHT, 2) 
for (let index = 0; index < 3; index++) {
    agent.move(FORWARD, 1)    	
    agent.place(UP)    	
}
```
```package
```
