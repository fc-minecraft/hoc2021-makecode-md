### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Pyramids of Giza.

## Step 1
The architect of the pyramids is trying to build a structure that will last the test of time. Teach them how to make a triangle by building one on the platform.


#### ~ tutorialhint 
Give the Agent `Smooth Stone` by using the ``||agent.setItem||`` block, then use the ``||agent.move||`` block to get the Agent in position and the ``||agent.place||`` block to place the `Smooth Stone`

```ghost
    agent.setItem(SMOOTH_SANDSTONE, 64, 1)
    agent.move(FORWARD, 1)
    agent.place(BACK)
    agent.move(FORWARD, 1)
    agent.place(BACK)
    agent.move(FORWARD, 1)
    agent.place(BACK)
    agent.move(FORWARD, 1)
    agent.place(BACK)
    agent.move(FORWARD, 1)
    agent.place(BACK)
    agent.move(UP, 1)
    agent.turn(LEFT_TURN)
    agent.turn(LEFT_TURN)
    agent.move(FORWARD, 3)
    agent.place(BACK)
    agent.move(FORWARD, 1)
    agent.place(BACK)
    agent.move(FORWARD, 1)
    agent.place(BACK)
    agent.move(UP, 1)
    agent.turn(LEFT_TURN)
    agent.turn(LEFT_TURN)
    agent.move(FORWARD, 3)
    agent.place(BACK)
```
```template
\\
```
```package
```
