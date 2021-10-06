### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Paleontology Puzzle

## Step 1
Some of the fossils were replaced with sand! Break the sand blocks and replace them with bone blocks before the Paleontologist notices.


#### ~ tutorialhint 
Give the Agent at least 4 `Bone Block` by using ``||agent.agent set item||``, then use ``||agent.agent move||`` to move the Agent into position, ``||agent.agent destroy||`` to break the sand and ``||agent.agent place||`` to place the `Bone Block`.

```ghost
    agent.setItem(BONE_BLOCK, 64, 1)
    agent.move(FORWARD, 0)
    agent.destroy(FORWARD)
    agent.place(FORWARD)
    for (let index = 0; index < 4; index++) {
    	
    }
```
```template
\\
```
```package
```
