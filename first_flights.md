### @flyoutOnly true
### @hideIteration true
### @explicitHints true

#First Flight

## Step 1
The first flight is scheduled to take off any minute now, but someone came and put holes in the runway! Use the Agent to fill the holes so the airplane can have a smooth take off.


#### ~ tutorialhint 
Give the Agent `Dirt` by using ``||agent.agent set item||``, then use ``||agent.agent move||`` to move the Agent and ``||agent.agent place||`` to place the `Dirt`.

```ghost
    agent.setItem(DIRT, 64, 1)
    agent.move(FORWARD, 1)
    agent.place(DOWN)
    agent.move(FORWARD, 1)
    agent.place(DOWN)
    agent.move(FORWARD, 3)
    agent.move(RIGHT, 2)
    agent.place(DOWN)
    agent.move(FORWARD, 1)
    agent.place(DOWN)
    agent.move(FORWARD, 3)
    agent.move(LEFT, 2)
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
