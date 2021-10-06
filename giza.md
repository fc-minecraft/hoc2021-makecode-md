### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Pyramids of Giza

## Step 1
The Architect of the pyramids is trying to build a structure that will last the test of time. Teach them how to make a pyramid by building a 3 layer triangle on the platform.


#### ~ tutorialhint 
Give the Agent `Smooth Stone` by using ``||agent.agent set item||``, then use ``||agent.agent move||`` to move the Agent into position and ``||agent.agent place||`` to place the `Smooth Stone`.

```ghost
    agent.setItem(SMOOTH_SANDSTONE, 64, 0)
    agent.move(FORWARD, 0)
    agent.place(FORWARD)
    agent.turn(LEFT_TURN)
    for (let index = 0; index < 4; index++) {
    	
    }
```
```template
\\
```
```package
```
