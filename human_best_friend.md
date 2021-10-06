### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Human's Best Friends

## Step 1
Humans made dogs their friends thousands of years ago. But something scared away the dogs this time. Use the Agent to leave a trail of beets 5 blocks apart that the wolves can follow to the human's camp.


#### ~ tutorialhint 
Use ``||agent.agent move||`` to move the Agent towards the camp site, and then use ``||agent.agent drop||`` to drop a ``Beet`` every 5 blocks.

```ghost
    agent.move(FORWARD, 0)
    agent.drop(FORWARD, 0, 0)
    for (let index = 0; index < 4; index++) {
    	
    }
```
```template
\\
```
```package
```
