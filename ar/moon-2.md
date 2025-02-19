### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Mission Moon (Debug)

## Step 1 
هناك خطأ في الكود أدناه. اضغط على زر التشغيل الأخضر لتشغيله ومعرفة ما يحدث، ثم قم بتصحيح الأخطاء لتكتشف ما هو الخطأ وما التعديلات اللازمة لجعله يعمل بشكل صحيح.

#### ~ tutorialhint  
استخدم ``||agent.agent move||`` و ``||agent.agent turn||`` داخل البلوك ``||blocks.on start||`` لترسل الحسابات إلى وحدة الفضاء. استخدم حسابات الرياضي لمساعدتك في تحديد المسار الذي يجب أن يسلكه الروبوت. تقدم 25 خطوة، ثم اتجه يمينا 17 خطوة، ثم 3 خطوات للأسفل.

```ghost
    agent.move(FORWARD, 0)
    agent.turn(RIGHT_TURN)
```
```template
agent.move(FORWARD, 25)
agent.turn(RIGHT_TURN)
agent.move(FORWARD, 17)
agent.turn(LEFT_TURN)
agent.move(UP, 3)
```
```package
```
