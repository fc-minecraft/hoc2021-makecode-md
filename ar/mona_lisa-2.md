### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# The Mona Lisa (Debug)

## Step 1
هناك خطأ في الكود أدناه. اضغط على زر التشغيل الأخضر لتشغيله ومعرفة ما يحدث، ثم قم بتصحيح الأخطاء لتكتشف ما هو الخطأ وما التعديلات اللازمة لجعله يعمل بشكل صحيح.

#### ~ tutorialhint  
استخدم ``||agent:وكيل ينقل||`` لتحريك الروبوت، ثم استخدم ``||agent:وكيل يضع||`` لوضع الـ `White Glazed Terracotta` لذي قدمناه للروبوت. كرر استخدام ``||agent:وكيل ينقل||`` و ``||agent:وكيل يضع||`` حتى يتم وضع العدد المطلوب من البلوكات.

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
agent.turn(LEFT_TURN)
for (let index = 0; index < 5; index++) {
    agent.move(FORWARD, 1)
    agent.place(DOWN)    	
}
```
```package
```
