### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# First Flight (Debug)

## Step 1
يوجد خطأ في الكود المرفق أدناه. اضغط على زر التشغيل الأخضر لتشغيله ومعرفة ما يحدث، ثم قم بتصحيح الأخطاء لتحديد المشكلة والتعديلات المطلوبة لجعله يعمل بشكل صحيح.

#### ~ tutorialhint  
استخدم ``||agent.agent move||`` لإرسال الروبوت إلى الحفرة. املأ كل حفرة باستخدام ``||agent.agent place||``إلى وضع الـ `Dirt` البلوك الذي قدمناه للروبوت. كرر. ``||agent.agent move||`` و ``||agent.agent place||`` حتى يتم ملء جميع الحفر.

```ghost
    agent.move(FORWARD, 0)
    agent.place(FORWARD)
    for (let index = 0; index < 4; index++) {
    	
    }
```
```template
for (let index = 0; index < 3; index++) {
    agent.move(FORWARD, 1)    	
    agent.place(UP)
}
agent.move(FORWARD, 2)  
agent.move(RIGHT, 2)  
for (let index = 0; index < 3; index++) {
    agent.move(FORWARD, 1)    	
    agent.place(UP)    	
}
agent.move(FORWARD, 2)  
agent.move(RIGHT, 2) 
for (let index = 0; index < 3; index++) {
    agent.move(FORWARD, 1)    	
    agent.place(UP)    	
}
```
```package
```
