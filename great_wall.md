### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# The Great Wall of China

## Step 1
Pandas keep eating the bamboo scaffolding, stopping the workers from getting high enough to complete the wall. Plant 5 pieces of bamboo to lead the pandas away from the wall so the workers can complete their work.


#### ~ tutorialhint 
Give the Agent `Bamboo` by using ``||agent.setItem||``, then use the ``||agent.move||`` to move the Agent into position and ``||agent.place||`` to place the `Bamboo`.

```ghost
    agent.setItem(BAMBOO, 64, 1)
    agent.place(DOWN)
    agent.move(FORWARD, 1)
    agent.place(DOWN)
    agent.move(FORWARD, 1)
    agent.place(DOWN)
    agent.move(FORWARD, 1)
    agent.place(DOWN)
    agent.move(FORWARD, 1)
    agent.place(DOWN)
    for (let index = 0; index < 4; index++) {
    	
    }
```
```template
\\
```
```package
```
