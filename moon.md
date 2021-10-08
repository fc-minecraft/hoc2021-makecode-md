### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Mission Moon

## Step 1
You need to dock your agent with the space module. You cannot count the spaces that the AGENT must move to complete the mission. You might want to think about the moves required before coding and you will need to use the information the Mathematician provides to complete the task.

#### ~ tutorialhint 
Use the ``||agent.agent move||`` and ``||agent.agent turn||`` blocks within the ``||blocks.on start||`` block to position your agent forward 25, right 17, and down 3.

```ghost
    agent.move(FORWARD, 0)
    agent.turn(RIGHT_TURN)
```
```template
\\
```
```package
```
