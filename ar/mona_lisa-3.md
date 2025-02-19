### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# The Mona Lisa (Solution)

## Step 1
الكود الموجود أدناه يمثل الحل الصحيح للنشاط. يمكنك تشغيله من خلال الضغط على زر التشغيل الأخضر لمشاهدة كيفية عمله.

#### ~ tutorialhint  
استخدم ``||agent.agent move||`` لتحريك الروبوت، ثم استخدم ``||agent.agent place||`` لوضع الـ `White Glazed Terracotta` الذي قدمناه للروبوت. كرر استخدام ``||agent.agent move||`` و ``||agent.agent place||`` حتى يتم وضع العدد المطلوب من البلوكات.

```ghost
    agent.move(FORWARD, 0)
    agent.place(FORWARD)
    agent.turn(RIGHT_TURN)
    for (let index = 0; index < 4; index++) {
    	
    }
```
```template
for (let index = 0; index < 5; index++) {
    agent.move(FORWARD, 1)
    agent.place(DOWN)
}
agent.turn(RIGHT_TURN)
for (let index = 0; index < 5; index++) {
    agent.move(FORWARD, 1)
    agent.place(DOWN)    	
}
```
```package
```
