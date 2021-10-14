### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Mission Moon

## Step 1
Send your agent to the space module to deliver the calculations. Think about the moves required and use the Mathematician's calculations to determine how many moves the agent must make.

#### ~ tutorialhint 
Use the ``||agent.agent move||`` and ``||agent.agent turn||`` blocks within the ``||blocks.on start||`` block to deliver the calculations to the space module. Use the Mathematician’s calculations to help you determine the path the Agent should take. Forward 25, right 17, and down 3.

```ghost
    agent.move(FORWARD, 0)
    agent.turn(RIGHT_TURN)
```
```template
\\
```
```package
```
