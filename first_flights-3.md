### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# First Flight (Solution)

## Step 1
The below code is the correct solution to the activity. Run the code by pressing the green play button to see it in action.

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
agent.setItem(DIRT, 64, 0)
for (let index = 0; index < 2; index++) {
    agent.move(FORWARD, 1)    	
    agent.place(DOWN)
}
agent.move(FORWARD, 2)  
agent.move(RIGHT, 2)  
for (let index = 0; index < 2; index++) {
    agent.move(FORWARD, 1)    	
    agent.place(DOWN)    	
}
agent.move(FORWARD, 2)  
agent.move(RIGHT, 2) 
for (let index = 0; index < 2; index++) {
    agent.move(FORWARD, 1)    	
    agent.place(DOWN)    	
}
```
```package
```
