### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# The Great Wall of China

## Step 1
Pandas keep eating the bamboo scaffolding stopping the Engineer from getting high enough to complete the wall. Plant 5 pieces of bamboo to lead the pandas away from the wall.


#### ~ tutorialhint 
Give the Agent `Bamboo` by using ``||agent.agent set item||``, then use the ``||agent.agent move||`` to move the Agent into position and ``||agent.agent place||`` to place the `Bamboo`.

```ghost
    agent.setItem(BAMBOO, 64, 0)
    agent.place(FORWARD)
    agent.move(FORWARD, 0)
    for (let index = 0; index < 4; index++) {
    	
    }
```
```template
\\
```
```package
```
