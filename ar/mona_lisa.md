### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# The Mona Lisa

## Step 1
The Mona Lisa lost her famous smile. You will need to place the `White Glazed Terracotta` blocks we've given the Agent to form a square outline which is 6 blocks in length by 6 blocks in width.

#### ~ tutorialhint  
استخدم ``||agent:وكيل ينقل||`` لتحريك الروبوت، ثم استخدم ``||agent:وكيل يضع||`` لوضع الـ `White Glazed Terracotta` الذي قدمناه للروبوت. كرر استخدام ``||agent:وكيل ينقل||`` و ``||agent:وكيل يضع||`` حتى يتم وضع العدد المطلوب من البلوكات

```ghost
    agent.move(FORWARD, 0)
    agent.place(FORWARD)
    agent.turn(RIGHT_TURN)
    for (let index = 0; index < 4; index++) {
    	
    }
```
```template
\\
```
```package
```
