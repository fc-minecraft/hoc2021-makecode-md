### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Mission Moon

## Step 1
Send your Agent to dock with the module to deliver the information. You won't be able to count the Agent's movement, so you'll need to rely on the calculations given to you by the space engineer. 

#### ~ tutorialhint 
Use ``||agent.agent move||`` to dock the Agent with the moon module by moving it forward 25, right 17, and down 3.

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
