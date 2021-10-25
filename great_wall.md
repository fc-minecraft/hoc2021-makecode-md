### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# The Great Wall of China

## Step 1
The Pandas keep eating the bamboo scaffolding, stopping the Engineer from completing the wall. Lead the pandas away from the wall. Code your Agent to place 5 `Bamboo` pieces in the field.

#### ~ tutorialhint 
Use ``||agent.agent set block or item||`` to make sure your Agent places `Bamboo`. Use the ``||agent.agent move||`` block to position your Agent and ``||agent.agent place||`` to place the `Bamboo` in the direction you want it placed.

```ghost
    agent.setItem(BAMBOO, 64, 0)
    agent.place(FORWARD)
    agent.move(FORWARD, 0)
    for (let index = 0; index < 4; index++) {
    	
    }
```
```template
agent.setItem(BAMBOO, 64, 1)
```
```package
```
