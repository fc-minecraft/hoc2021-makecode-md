### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Mission Moon

## Step 1
Dock your agent with the space module. You cannot count the spaces that the AGENT must move to complete the mission. Think about the moves required and use the Mathematician's information.

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
