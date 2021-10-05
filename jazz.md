### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Big Band Jazz.

## Step 1
The Jazz musician lost his trumpet and has been playing the kazoo. Use the Agent to get through the maze and collect the trumpet to help restore history!


#### ~ tutorialhint 
Use the ``||agent.move||`` block get through the maze and the ``||agent.collectAll||`` block to pick it up.

```ghost
    agent.move(FORWARD, 3)
    agent.move(UP, 1)
    agent.move(FORWARD, 2)
    agent.move(DOWN, 2)
    agent.move(FORWARD, 2)
    agent.move(UP, 2)
    agent.move(FORWARD, 1)
    agent.collectAll()
```
```template
\\
```
```package
```
