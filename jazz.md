### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Big Band Jazz

## Step 1
The Jazz Musician has lost his trumpet and is using a kazoo instead. Code your AGENT through the maze and collect the trumpet.

#### ~ tutorialhint 
Drag ``||agent.agent move||`` into ``||blocks.on start||`` to give instructions to your agent on how to move. Change the direction (UP, DOWN, LEFT, RIGHT) and number to make the AGENT move the right number of steps. At the end of your code use ``||agent.agent collect all||`` to collect the trumpet.
```ghost
    agent.move(FORWARD, 0)
    agent.collectAll()
```
```template
\\
```
```package
```
