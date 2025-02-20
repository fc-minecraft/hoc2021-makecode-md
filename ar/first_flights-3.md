### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# First Flight (Solution)

## Step 1
الكود الموجود أدناه يمثل الحل الصحيح للنشاط. يمكنك تشغيله من خلال الضغط على زر التشغيل الأخضر لمشاهدة كيفية عمله.

#### ~ tutorialhint  
استخدم ``||agent:وكيل ينقل||`` لإرسال الروبوت إلى الحفرة. املأ كل حفرة باستخدام``||agent:وكيل يضع||`` إلى وضع الـ `التراب`البلوك الذي قدمناه للروبوت. كرر. ``||agent:وكيل ينقل||`` و ``||agent:وكيل يضع||`` حتى يتم ملء جميع الحفر.

```ghost
    agent.move(FORWARD, 0)
    agent.place(FORWARD)
    for (let index = 0; index < 4; index++) {
    	
    }
```
```template
for (let index = 0; index < 2; index++) {
    agent.move(FORWARD, 1)    	
    agent.place(DOWN)
}
agent.move(FORWARD, 2)  
agent.move(RIGHT, 2)  
for (let index = 0; index < 2; index++) {
    agent.move(FORWARD, 1)    	
    agent.place(DOWN)    	
}
agent.move(FORWARD, 2)  
agent.move(RIGHT, 2) 
for (let index = 0; index < 2; index++) {
    agent.move(FORWARD, 1)    	
    agent.place(DOWN)    	
}
```
```package
```
