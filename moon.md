### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Mission Moon

## Step 1
The Apollo 11 crew is stuck orbiting the moon without the information they need to land. Send your Agent to dock with the module to deliver the information. You won't be able to count the Agent's movement from here in the control center, so you'll need to rely on the calculations given to you by the space engineer. Forward 25, Right 17, Down 3.


#### ~ tutorialhint 
Use ``||agent.move||`` to dock the Agent with the moon module by moving it forward 25, right 17, and down 3.

```ghost
    agent.move(FORWARD, 25)
    agent.turn(RIGHT_TURN)
    agent.move(FORWARD, 17)
    agent.move(DOWN, 3)
```
```template
\\
```
```package
```
