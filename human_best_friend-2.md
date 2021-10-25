### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Human's Best Friends (Debug)

## Step 1
There's something wrong with the below code. Press the green play button to run it to see what happens, and then debug it to see what's wrong and what changes are needed to make it work.
#### ~ tutorialhint 
Give your Agent ``Beet`` items by using the ``||agent.agent set block or item||``. Move your Agent to the right place using ``||agent.agent move||`` and ``||agent.agent turn||``. At the right point use ``||agent.agent drop||`` to drop a ``Beet``. Repeat this until the right number of BEETS are placed 5 blocks apart.

```ghost
    agent.setItem(BEETROOT, 64, 0)
    agent.move(FORWARD, 0)
    agent.drop(FORWARD, 0, 0)
    for (let index = 0; index < 4; index++) {
    	
    }
```
```template
agent.setItem(BEETROOT, 64, 1)
for (let index = 0; index < 5; index++) {
    agent.drop(FORWARD, 1, 1)
    agent.move(FORWARD, 1)
}
```
```package
```
