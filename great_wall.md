### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# The Great Wall of China

## Step 1
The Pandas keep eating the bamboo scaffolding and stopping the Engineer from getting to the right part of the wall and completing it. To solve this challenge, code your AGENT to place 5 pieces of bamboo that will lead the pandas away from the wall.

#### ~ tutorialhint 
Use ``||agent.agent set block or item||`` to make sure your AGENT places `Bamboo`. Use the ``||agent.agent move||`` block to position your AGENT and ``||agent.agent place||`` to place the `Bamboo`.

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
