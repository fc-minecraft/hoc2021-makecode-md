### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Great Pyramid at Giza (Debug)

## Step 1
هناك خطأ في الكود أدناه. اضغط على زر التشغيل الأخضر لتشغيله ومعرفة ما يحدث، ثم قم بتصحيح الأخطاء لتكتشف ما هو الخطأ وما التعديلات اللازمة لجعله يعمل بشكل صحيح.

#### ~ tutorialhint  
فكر في كيفية تحرك الروبوت لوضع العدد المناسب من الكتل لكل مستوى من مستويات الهرم. استخدم الـ``||agent.agent move||`` استخدم البلوك لتحريك الروبوت للأمام، واستخدمه في كل خطوة. ``||agent.agent place||``إلى وضع الـ `Smooth Sandstone` الذي قدمناه للروبوت.

```ghost
    agent.move(FORWARD, 0)
    agent.place(FORWARD)
    agent.turn(LEFT_TURN)
    for (let index = 0; index < 4; index++) {
    	
    }
```
```template
for (let index=0); index < 3; index++){
agent.move(FORWARD, 1)
agent.place(BACK)
}
agent.move(UP, 1)
agent.turn(LEFT_TURN)
agent.turn(RIGHT_TURN)
agent.move(FORWARD, 1)
agent.move(FORWARD, 1)
agent.move(FORWARD, 1)
agent.place(UP)
```
```package
```
