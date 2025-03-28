### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# الموناليزا

## الخطوة 1
فقدت لوحة الموناليزا ابتسامتها الشهيرة. ستحتاج إلى وضع بلوك `الفخار` التي قدمناها للروبوت لتشكيل إطار مربع بطول 6 بلوكات وعرض 6 بلوكات.

#### ~ tutorialhint 
استخدم بلوك ``||agent:وكيل ينقل||`` لتحريك الروبوت، ثم استخدم بلوك ``||agent:وكيل يضع||`` لوضع `الفخار` الذي قدمناه للروبوت. كرر استخدام بلوك ``||agent:وكيل ينقل||`` و  بلوك ``||agent:وكيل يضع||`` حتى يتم وضع العدد المطلوب من البلوكات.

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

