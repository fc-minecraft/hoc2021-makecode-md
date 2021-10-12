### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Human's Best Friends

## Step 1
Dogs have been friends with people for thousands of years. But, something has scared the dogs away. Code your AGENT to leave ``Beet`` items 5 blocks apart, so the wolves come to the people at the camp.

#### ~ tutorialhint 
Give your AGENT ``Beet`` items by using the ``||agent.agent set block or item||`` to ``Beet``. Move your AGENT to the right place using A``||agent.agent move||`` and ``||agent.agent turn||``. At the right point use ``||agent.agent drop||`` to drop a ``Beet``. Repeat this until the right number of BEETS are placed.

```ghost
    agent.setItem(BEET, 64, 0)
    agent.move(FORWARD, 0)
    agent.drop(FORWARD, 0, 0)
    for (let index = 0; index < 4; index++) {
    	
    }
```
```template
\\
```
```package
```
