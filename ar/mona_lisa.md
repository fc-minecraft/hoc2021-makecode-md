### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# The Mona Lisa

## Step 1
فقدت لوحة الموناليزا ابتسامتها الشهيرة. ستحتاج إلى وضع بلوك `الطين الأبيض المزجج` التي قدمناها للروبوت لتشكيل إطار مربع بطول 6 بلوكات وعرض 6 بلوكات.

#### ~ tutorialhint  
استخدم ``||agent:وكيل ينقل||`` لتحريك الروبوت، ثم استخدم ``||agent:وكيل يضع||`` لوضع الـ `الطين الأبيض المزجج` الذي قدمناه للروبوت. كرر استخدام ``||agent:وكيل ينقل||`` و ``||agent:وكيل يضع||`` حتى يتم وضع العدد المطلوب من البلوكات

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
 
