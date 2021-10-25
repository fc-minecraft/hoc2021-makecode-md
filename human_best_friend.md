### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Human's Best Friends

## Step 1
Dogs have been friends with people for thousands of years. But, something has scared the dogs away. Code your Agent to leave ``Beet`` items 5 blocks apart to help the people tame the wolves into dogs.
#### ~ tutorialhint 
Give your Agent ``Beetroot`` items by using the ``||agent.agent set block or item||``. Move your Agent to the right place using ``||agent.agent move||`` and ``||agent.agent turn||``. At the right point use ``||agent.agent drop||`` to drop a ``Beet``. Repeat this until the right number of BEETS are placed 5 blocks apart.

```ghost
    agent.setItem(BEETROOT, 64, 0)
    agent.move(FORWARD, 0)
    agent.drop(FORWARD, 0, 0)
    for (let index = 0; index < 4; index++) {
    	
    }
```
```template
agent.setItem(BEETROOT, 64, 0)
```
```package
```
